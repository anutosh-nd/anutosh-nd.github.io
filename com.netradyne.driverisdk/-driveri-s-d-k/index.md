---
title: DriveriSDK -
---
//[Netradyne Driveri SDK](../../index.md)/[com.netradyne.driverisdk](../index.md)/[DriveriSDK](index.md)



# DriveriSDK  
 [common] class [DriveriSDK](index.md)

Core interface for obtaining instances of all ND API classes.

   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| <a name="com.netradyne.driverisdk/DriveriSDK/DriveriSDK/#/PointingToDeclaration/"></a>[DriveriSDK](-driveri-s-d-k.md)| <a name="com.netradyne.driverisdk/DriveriSDK/DriveriSDK/#/PointingToDeclaration/"></a> [common] fun [DriveriSDK](-driveri-s-d-k.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| <a name="com.netradyne.driverisdk/DriveriSDK/apiEnv/#kotlin.String/PointingToDeclaration/"></a>[apiEnv](api-env.md)| <a name="com.netradyne.driverisdk/DriveriSDK/apiEnv/#kotlin.String/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [apiEnv](api-env.md)(env: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br>More info  <br>This function is available only for Driveri app  <br><br><br>
| <a name="kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/"></a>[equals](../../com.netradyne.driverisdk.video/-n-d-video-a-p-i/index.md#%5Bkotlin%2FAny%2Fequals%2F%23kotlin.Any%3F%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)| <a name="kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/"></a>[common]  <br>Content  <br>open operator fun [equals](../../com.netradyne.driverisdk.video/-n-d-video-a-p-i/index.md#%5Bkotlin%2FAny%2Fequals%2F%23kotlin.Any%3F%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| <a name="com.netradyne.driverisdk/DriveriSDK/getAPIClient/#/PointingToDeclaration/"></a>[getAPIClient](get-a-p-i-client.md)| <a name="com.netradyne.driverisdk/DriveriSDK/getAPIClient/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [getAPIClient](get-a-p-i-client.md)(): [NDAPIClient](../../com.netradyne.driverisdk.api/-n-d-a-p-i-client/index.md)  <br><br><br>
| <a name="com.netradyne.driverisdk/DriveriSDK/getAuthAPI/#/PointingToDeclaration/"></a>[getAuthAPI](get-auth-a-p-i.md)| <a name="com.netradyne.driverisdk/DriveriSDK/getAuthAPI/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [getAuthAPI](get-auth-a-p-i.md)(): [NDAuthAPI](../../com.netradyne.driverisdk.auth/-n-d-auth-a-p-i/index.md)  <br>More info  <br>Get an instance of [NDAuthAPI](../../com.netradyne.driverisdk.auth/-n-d-auth-a-p-i/index.md)  <br><br><br>
| <a name="com.netradyne.driverisdk/DriveriSDK/getCoachingAPI/#/PointingToDeclaration/"></a>[getCoachingAPI](get-coaching-a-p-i.md)| <a name="com.netradyne.driverisdk/DriveriSDK/getCoachingAPI/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [getCoachingAPI](get-coaching-a-p-i.md)(): [Either](../-either/index.md)<[NDError](../-n-d-error/index.md), [NDCoachingAPI](../../com.netradyne.driverisdk.coaching/-n-d-coaching-a-p-i/index.md)>  <br>More info  <br>Get an instance of [NDCoachingAPI](../../com.netradyne.driverisdk.coaching/-n-d-coaching-a-p-i/index.md).  <br><br><br>
| <a name="com.netradyne.driverisdk/DriveriSDK/getEventAccessAPI/#/PointingToDeclaration/"></a>[getEventAccessAPI](get-event-access-a-p-i.md)| <a name="com.netradyne.driverisdk/DriveriSDK/getEventAccessAPI/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [getEventAccessAPI](get-event-access-a-p-i.md)(): [Either](../-either/index.md)<[NDError](../-n-d-error/index.md), [NDEventAccessAPI](../../com.netradyne.driverisdk.eventAccess/-n-d-event-access-a-p-i/index.md)>  <br>More info  <br>Get an instance of [NDEventAccessAPI](../../com.netradyne.driverisdk.eventAccess/-n-d-event-access-a-p-i/index.md).  <br><br><br>
| <a name="com.netradyne.driverisdk/DriveriSDK/getEventsAPI/#/PointingToDeclaration/"></a>[getEventsAPI](get-events-a-p-i.md)| <a name="com.netradyne.driverisdk/DriveriSDK/getEventsAPI/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [getEventsAPI](get-events-a-p-i.md)(): [Either](../-either/index.md)<[NDError](../-n-d-error/index.md), [NDEventsAPI](../../com.netradyne.driverisdk.events/-n-d-events-a-p-i/index.md)>  <br>More info  <br>Get an instance of [NDEventsAPI](../../com.netradyne.driverisdk.events/-n-d-events-a-p-i/index.md).  <br><br><br>
| <a name="com.netradyne.driverisdk/DriveriSDK/getGreenzoneAPI/#/PointingToDeclaration/"></a>[getGreenzoneAPI](get-greenzone-a-p-i.md)| <a name="com.netradyne.driverisdk/DriveriSDK/getGreenzoneAPI/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [getGreenzoneAPI](get-greenzone-a-p-i.md)(): [Either](../-either/index.md)<[NDError](../-n-d-error/index.md), [NDGreenzoneAPI](../../com.netradyne.driverisdk.greenzone/-n-d-greenzone-a-p-i/index.md)>  <br>More info  <br>Get an instance of [NDGreenzoneAPI](../../com.netradyne.driverisdk.greenzone/-n-d-greenzone-a-p-i/index.md).  <br><br><br>
| <a name="com.netradyne.driverisdk/DriveriSDK/getUserAPI/#/PointingToDeclaration/"></a>[getUserAPI](get-user-a-p-i.md)| <a name="com.netradyne.driverisdk/DriveriSDK/getUserAPI/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [getUserAPI](get-user-a-p-i.md)(): [NDUserAPI](../../com.netradyne.driverisdk.user/-n-d-user-a-p-i/index.md)  <br>More info  <br>Get an instance of [NDUserAPI](../../com.netradyne.driverisdk.user/-n-d-user-a-p-i/index.md).  <br><br><br>
| <a name="com.netradyne.driverisdk/DriveriSDK/getVideoAPI/#/PointingToDeclaration/"></a>[getVideoAPI](get-video-a-p-i.md)| <a name="com.netradyne.driverisdk/DriveriSDK/getVideoAPI/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [getVideoAPI](get-video-a-p-i.md)(): [Either](../-either/index.md)<[NDError](../-n-d-error/index.md), [NDVideoAPI](../../com.netradyne.driverisdk.video/-n-d-video-a-p-i/index.md)>  <br>More info  <br>Get an instance of [NDVideoAPI](../../com.netradyne.driverisdk.video/-n-d-video-a-p-i/index.md).  <br><br><br>
| <a name="kotlin/Any/hashCode/#/PointingToDeclaration/"></a>[hashCode](../../com.netradyne.driverisdk.video/-n-d-video-a-p-i/index.md#%5Bkotlin%2FAny%2FhashCode%2F%23%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)| <a name="kotlin/Any/hashCode/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>open fun [hashCode](../../com.netradyne.driverisdk.video/-n-d-video-a-p-i/index.md#%5Bkotlin%2FAny%2FhashCode%2F%23%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| <a name="kotlin/Any/toString/#/PointingToDeclaration/"></a>[toString](../../com.netradyne.driverisdk.video/-n-d-video-a-p-i/index.md#%5Bkotlin%2FAny%2FtoString%2F%23%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)| <a name="kotlin/Any/toString/#/PointingToDeclaration/"></a>[common]  <br>Content  <br>open fun [toString](../../com.netradyne.driverisdk.video/-n-d-video-a-p-i/index.md#%5Bkotlin%2FAny%2FtoString%2F%23%2FPointingToDeclaration%2F%5D%2FFunctions%2F-1360578461)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

