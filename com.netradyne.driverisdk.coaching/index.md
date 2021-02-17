---
title: com.netradyne.driverisdk.coaching -
---
//[Netradyne Driveri SDK](../index.md)/[com.netradyne.driverisdk.coaching](index.md)



# Package com.netradyne.driverisdk.coaching  


## Types  
  
|  Name|  Summary| 
|---|---|
| <a name="com.netradyne.driverisdk.coaching/NDCoachingAPI///PointingToDeclaration/"></a>[NDCoachingAPI](-n-d-coaching-a-p-i/index.md)| <a name="com.netradyne.driverisdk.coaching/NDCoachingAPI///PointingToDeclaration/"></a>[common]  <br>Content  <br>class [NDCoachingAPI](-n-d-coaching-a-p-i/index.md) : NDApi  <br>More info  <br>Core interface for managing driver's weekly review sessions.  <br><br><br>
| <a name="com.netradyne.driverisdk.coaching/NDWeeklyReviewSession///PointingToDeclaration/"></a>[NDWeeklyReviewSession](-n-d-weekly-review-session/index.md)| <a name="com.netradyne.driverisdk.coaching/NDWeeklyReviewSession///PointingToDeclaration/"></a>[common]  <br>Content  <br>data class [NDWeeklyReviewSession](-n-d-weekly-review-session/index.md)(**sessionId**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **description**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **createdAt**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **driverId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **driverName**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **sessionStartTime**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **sessionEndTime**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **driverStarsCount**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **subTenantId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **tenantId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **eventIds**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)>?, **eventType**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **driverStarIds**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)>?, **greenzoneVersion**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **sessionAge**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, **vcStatus**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))  <br>More info  <br>This class represents a weekly review session generated for driver.  <br><br><br>
| <a name="com.netradyne.driverisdk.coaching/NDWeeklyReviewSessionDetail///PointingToDeclaration/"></a>[NDWeeklyReviewSessionDetail](-n-d-weekly-review-session-detail/index.md)| <a name="com.netradyne.driverisdk.coaching/NDWeeklyReviewSessionDetail///PointingToDeclaration/"></a>[common]  <br>Content  <br>data class [NDWeeklyReviewSessionDetail](-n-d-weekly-review-session-detail/index.md)(**sessionId**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **createdAt**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **driverId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **sessionStartTime**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **sessionEndTime**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **driverStarsCount**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **subTenantId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **tenantId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **eventIds**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)>?, **eventType**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **driverStarIds**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)>?, **greenzoneVersion**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **vcStatus**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **alertsInSession**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[NDEvent](../com.netradyne.driverisdk.events/-n-d-event/index.md)>, **driverStarsInSession**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[NDEvent](../com.netradyne.driverisdk.events/-n-d-event/index.md)>)  <br>More info  <br>Weekly review session detail  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| <a name="com.netradyne.driverisdk.coaching//toJSONString/kotlin.collections.List[com.netradyne.driverisdk.coaching.NDWeeklyReviewSession]#/PointingToDeclaration/"></a>[toJSONString](to-j-s-o-n-string.md)| <a name="com.netradyne.driverisdk.coaching//toJSONString/kotlin.collections.List[com.netradyne.driverisdk.coaching.NDWeeklyReviewSession]#/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[NDWeeklyReviewSession](-n-d-weekly-review-session/index.md)>.[toJSONString](to-j-s-o-n-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br>More info  <br>Get a JSON string representation for a list of [NDWeeklyReviewSession](-n-d-weekly-review-session/index.md)  <br><br><br>
