---
title: NDEventAccessAPI -
---
//[Netradyne Driveri SDK](../../index.md)/[com.netradyne.driverisdk.eventAccess](../index.md)/[NDEventAccessAPI](index.md)



# NDEventAccessAPI  
 [common] class [NDEventAccessAPI](index.md) : NDApi

Core interface for managing event access requests. An user should be either SafetyManager or a driver in self coaching mode to access these APIs. Else, these APIs will return [FEATURE_NOT_AVAILABLE](../../com.netradyne.driverisdk/-f-e-a-t-u-r-e_-n-o-t_-a-v-a-i-l-a-b-l-e.md) error code. Obtain an instance by calling DriveriSDK getEventAccessAPI.



Use [cancel](cancel.md) when the corresponding lifecycle-aware component or view is destroyed to cancel any ongoing network calls

   


## Functions  
  
|  Name|  Summary| 
|---|---|
| <a name="com.netradyne.driverisdk.eventAccess/NDEventAccessAPI/cancel/#/PointingToDeclaration/"></a>[cancel](cancel.md)| <a name="com.netradyne.driverisdk.eventAccess/NDEventAccessAPI/cancel/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>open override fun [cancel](cancel.md)()  <br><br><br>
| <a name="com.netradyne.driverisdk.eventAccess/NDEventAccessAPI/createVideoUploadRequest/#kotlin.collections.List[kotlin.Int]#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.Boolean,kotlin.Unit]/PointingToDeclaration/"></a>[createVideoUploadRequest](create-video-upload-request.md)| <a name="com.netradyne.driverisdk.eventAccess/NDEventAccessAPI/createVideoUploadRequest/#kotlin.collections.List[kotlin.Int]#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.Boolean,kotlin.Unit]/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [createVideoUploadRequest](create-video-upload-request.md)(videoCatalogIds: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>, callback: ([NDError](../../com.netradyne.driverisdk/-n-d-error/index.md)?, [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br>More info  <br>Create upload request for videoCatalogIds.  <br><br><br>
| <a name="kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/"></a>[equals](../../com.netradyne.driverisdk.video/-n-d-video-a-p-i/index.md#%5Bkotlin%2FAny%2Fequals%2F%23kotlin.Any%3F%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)| <a name="kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/"></a>[common]  <br>Content  <br>open operator fun [equals](../../com.netradyne.driverisdk.video/-n-d-video-a-p-i/index.md#%5Bkotlin%2FAny%2Fequals%2F%23kotlin.Any%3F%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| <a name="com.netradyne.driverisdk.eventAccess/NDEventAccessAPI/fetchVideosInEventAccessRequest/#kotlin.Int#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.collections.List[com.netradyne.driverisdk.video.NDVideo]?,kotlin.Unit]/PointingToDeclaration/"></a>[fetchVideosInEventAccessRequest](fetch-videos-in-event-access-request.md)| <a name="com.netradyne.driverisdk.eventAccess/NDEventAccessAPI/fetchVideosInEventAccessRequest/#kotlin.Int#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.collections.List[com.netradyne.driverisdk.video.NDVideo]?,kotlin.Unit]/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [fetchVideosInEventAccessRequest](fetch-videos-in-event-access-request.md)(requestId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), callback: ([NDError](../../com.netradyne.driverisdk/-n-d-error/index.md)?, [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[NDVideo](../../com.netradyne.driverisdk.video/-n-d-video/index.md)>?) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br>More info  <br>Get videos requested as part of event access request.  <br><br><br>
| <a name="com.netradyne.driverisdk.eventAccess/NDEventAccessAPI/getAssociatedVideos/#kotlin.Int#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.collections.List[com.netradyne.driverisdk.video.NDVideo]?,kotlin.Unit]/PointingToDeclaration/"></a>[getAssociatedVideos](get-associated-videos.md)| <a name="com.netradyne.driverisdk.eventAccess/NDEventAccessAPI/getAssociatedVideos/#kotlin.Int#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.collections.List[com.netradyne.driverisdk.video.NDVideo]?,kotlin.Unit]/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [getAssociatedVideos](get-associated-videos.md)(videoCatalogId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), callback: ([NDError](../../com.netradyne.driverisdk/-n-d-error/index.md)?, [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[NDVideo](../../com.netradyne.driverisdk.video/-n-d-video/index.md)>?) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br>More info  <br>Get videos associated with an outward video.  <br><br><br>
| <a name="com.netradyne.driverisdk.eventAccess/NDEventAccessAPI/getEventAccessRequests/#kotlin.Long#kotlin.Long#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.collections.List[com.netradyne.driverisdk.eventAccess.NDEventAccessRequest]?,kotlin.Unit]/PointingToDeclaration/"></a>[getEventAccessRequests](get-event-access-requests.md)| <a name="com.netradyne.driverisdk.eventAccess/NDEventAccessAPI/getEventAccessRequests/#kotlin.Long#kotlin.Long#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.collections.List[com.netradyne.driverisdk.eventAccess.NDEventAccessRequest]?,kotlin.Unit]/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [getEventAccessRequests](get-event-access-requests.md)(startTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), endTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), callback: ([NDError](../../com.netradyne.driverisdk/-n-d-error/index.md)?, [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[NDEventAccessRequest](../-n-d-event-access-request/index.md)>?) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br>More info  <br>Get event access requests created by the user in the time interval specified by startTime and endTime  <br><br><br>
| <a name="com.netradyne.driverisdk.eventAccess/NDEventAccessAPI/getVideoListFromDriveriForInterval/#kotlin.Long#kotlin.Long#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.collections.List[com.netradyne.driverisdk.eventAccess.NDVideoData]?,kotlin.Unit]/PointingToDeclaration/"></a>[getVideoListFromDriveriForInterval](get-video-list-from-driveri-for-interval.md)| <a name="com.netradyne.driverisdk.eventAccess/NDEventAccessAPI/getVideoListFromDriveriForInterval/#kotlin.Long#kotlin.Long#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.collections.List[com.netradyne.driverisdk.eventAccess.NDVideoData]?,kotlin.Unit]/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [getVideoListFromDriveriForInterval](get-video-list-from-driveri-for-interval.md)(startTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), endTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), callback: ([NDError](../../com.netradyne.driverisdk/-n-d-error/index.md)?, [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[NDVideoData](../-n-d-video-data/index.md)>?) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br>More info  <br>Get video list from Driveri for interval specified by startTime and endTime  <br><br><br>
| <a name="kotlin/Any/hashCode/#/PointingToDeclaration/"></a>[hashCode](../../com.netradyne.driverisdk.video/-n-d-video-a-p-i/index.md#%5Bkotlin%2FAny%2FhashCode%2F%23%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)| <a name="kotlin/Any/hashCode/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>open fun [hashCode](../../com.netradyne.driverisdk.video/-n-d-video-a-p-i/index.md#%5Bkotlin%2FAny%2FhashCode%2F%23%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| <a name="kotlin/Any/toString/#/PointingToDeclaration/"></a>[toString](../../com.netradyne.driverisdk.video/-n-d-video-a-p-i/index.md#%5Bkotlin%2FAny%2FtoString%2F%23%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)| <a name="kotlin/Any/toString/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>open fun [toString](../../com.netradyne.driverisdk.video/-n-d-video-a-p-i/index.md#%5Bkotlin%2FAny%2FtoString%2F%23%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
