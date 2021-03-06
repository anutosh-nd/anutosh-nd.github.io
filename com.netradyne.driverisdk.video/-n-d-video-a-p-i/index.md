---
title: NDVideoAPI -
---
//[Netradyne Driveri SDK](../../index.md)/[com.netradyne.driverisdk.video](../index.md)/[NDVideoAPI](index.md)



# NDVideoAPI  
 [common] class [NDVideoAPI](index.md) : NDApi

Core interface for requesting and playing videos captured by Driveri. Obtain an instance by calling DriveriSDK getVideoAPI.



Use [cancel](cancel.md) when the corresponding lifecycle-aware component or view is destroyed to cancel any ongoing network calls.

   


## Functions  
  
|  Name|  Summary| 
|---|---|
| <a name="com.netradyne.driverisdk.video/NDVideoAPI/cancel/#/PointingToDeclaration/"></a>[cancel](cancel.md)| <a name="com.netradyne.driverisdk.video/NDVideoAPI/cancel/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>open override fun [cancel](cancel.md)()  <br><br><br>
| <a name="kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/"></a>[equals](index.md#%5Bkotlin%2FAny%2Fequals%2F%23kotlin.Any%3F%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)| <a name="kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/"></a>[common]  <br>Content  <br>open operator fun [equals](index.md#%5Bkotlin%2FAny%2Fequals%2F%23kotlin.Any%3F%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| <a name="com.netradyne.driverisdk.video/NDVideoAPI/getPresignedAudioUrlForVideo/#com.netradyne.driverisdk.video.NDVideo#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.String?,kotlin.Unit]/PointingToDeclaration/"></a>[getPresignedAudioUrlForVideo](get-presigned-audio-url-for-video.md)| <a name="com.netradyne.driverisdk.video/NDVideoAPI/getPresignedAudioUrlForVideo/#com.netradyne.driverisdk.video.NDVideo#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.String?,kotlin.Unit]/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [getPresignedAudioUrlForVideo](get-presigned-audio-url-for-video.md)(video: [NDVideo](../-n-d-video/index.md), callback: ([NDError](../../com.netradyne.driverisdk/-n-d-error/index.md)?, [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br>More info  <br>Get presigned audio url for video if the video has audio associated with it.  <br><br><br>
| <a name="com.netradyne.driverisdk.video/NDVideoAPI/getPresignedUrlForDefaultEventVideo/#com.netradyne.driverisdk.events.NDEvent#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.String?,kotlin.Unit]/PointingToDeclaration/"></a>[getPresignedUrlForDefaultEventVideo](get-presigned-url-for-default-event-video.md)| <a name="com.netradyne.driverisdk.video/NDVideoAPI/getPresignedUrlForDefaultEventVideo/#com.netradyne.driverisdk.events.NDEvent#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.String?,kotlin.Unit]/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [getPresignedUrlForDefaultEventVideo](get-presigned-url-for-default-event-video.md)(event: [NDEvent](../../com.netradyne.driverisdk.events/-n-d-event/index.md), callback: ([NDError](../../com.netradyne.driverisdk/-n-d-error/index.md)?, [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br>More info  <br>Get presigned url for event's default video.  <br><br><br>
| <a name="com.netradyne.driverisdk.video/NDVideoAPI/getPresignedUrlForVideo/#com.netradyne.driverisdk.video.NDVideo#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.String?,kotlin.Unit]/PointingToDeclaration/"></a>[getPresignedUrlForVideo](get-presigned-url-for-video.md)| <a name="com.netradyne.driverisdk.video/NDVideoAPI/getPresignedUrlForVideo/#com.netradyne.driverisdk.video.NDVideo#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.String?,kotlin.Unit]/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [getPresignedUrlForVideo](get-presigned-url-for-video.md)(video: [NDVideo](../-n-d-video/index.md), callback: ([NDError](../../com.netradyne.driverisdk/-n-d-error/index.md)?, [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br>More info  <br>Get presigned url for video.  <br><br><br>
| <a name="kotlin/Any/hashCode/#/PointingToDeclaration/"></a>[hashCode](index.md#%5Bkotlin%2FAny%2FhashCode%2F%23%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)| <a name="kotlin/Any/hashCode/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>open fun [hashCode](index.md#%5Bkotlin%2FAny%2FhashCode%2F%23%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| <a name="com.netradyne.driverisdk.video/NDVideoAPI/requestEventVideo/#com.netradyne.driverisdk.events.NDEvent#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.Boolean,kotlin.Unit]/PointingToDeclaration/"></a>[requestEventVideo](request-event-video.md)| <a name="com.netradyne.driverisdk.video/NDVideoAPI/requestEventVideo/#com.netradyne.driverisdk.events.NDEvent#kotlin.Function2[com.netradyne.driverisdk.NDError?,kotlin.Boolean,kotlin.Unit]/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [requestEventVideo](request-event-video.md)(event: [NDEvent](../../com.netradyne.driverisdk.events/-n-d-event/index.md), callback: ([NDError](../../com.netradyne.driverisdk/-n-d-error/index.md)?, [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br>More info  <br>Request event's default video from Driveri.  <br><br><br>
| <a name="kotlin/Any/toString/#/PointingToDeclaration/"></a>[toString](index.md#%5Bkotlin%2FAny%2FtoString%2F%23%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)| <a name="kotlin/Any/toString/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>open fun [toString](index.md#%5Bkotlin%2FAny%2FtoString%2F%23%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

