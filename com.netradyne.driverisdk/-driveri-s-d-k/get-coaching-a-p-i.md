---
title: getCoachingAPI -
---
//[Netradyne Driveri SDK](../../index.md)/[com.netradyne.driverisdk](../index.md)/[DriveriSDK](index.md)/[getCoachingAPI](get-coaching-a-p-i.md)



# getCoachingAPI  
[common]  
Content  
fun [getCoachingAPI](get-coaching-a-p-i.md)(): [Either](../-either/index.md)<[NDError](../-n-d-error/index.md), [NDCoachingAPI](../../com.netradyne.driverisdk.coaching/-n-d-coaching-a-p-i/index.md)>  
More info  


Get an instance of [NDCoachingAPI](../../com.netradyne.driverisdk.coaching/-n-d-coaching-a-p-i/index.md). This method returns an [Either](../-either/index.md) type which can contain either an instance of [NDError](../-n-d-error/index.md) or [NDCoachingAPI](../../com.netradyne.driverisdk.coaching/-n-d-coaching-a-p-i/index.md). Use [Either.isLeft](../-either/is-left.md) and [Either.getLeft](../-either/get-left.md) or [Either.isRight](../-either/is-right.md) and [Either.getRight](../-either/get-right.md) to obtain the encapsulated instance.

  



