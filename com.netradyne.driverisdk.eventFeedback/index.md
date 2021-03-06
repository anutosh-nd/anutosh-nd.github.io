---
title: com.netradyne.driverisdk.eventFeedback -
---
//[Netradyne Driveri SDK](../index.md)/[com.netradyne.driverisdk.eventFeedback](index.md)



# Package com.netradyne.driverisdk.eventFeedback  


## Types  
  
|  Name|  Summary| 
|---|---|
| <a name="com.netradyne.driverisdk.eventFeedback/NDEventFeedback///PointingToDeclaration/"></a>[NDEventFeedback](-n-d-event-feedback/index.md)| <a name="com.netradyne.driverisdk.eventFeedback/NDEventFeedback///PointingToDeclaration/"></a>[common]  <br>Content  <br>data class [NDEventFeedback](-n-d-event-feedback/index.md)(**feedbackId**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **eventId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **categoryId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **image**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br>More info  <br>This class represents feedback for an event submitted by Driver.  <br><br><br>
| <a name="com.netradyne.driverisdk.eventFeedback/NDFeedbackCategory///PointingToDeclaration/"></a>[NDFeedbackCategory](-n-d-feedback-category/index.md)| <a name="com.netradyne.driverisdk.eventFeedback/NDFeedbackCategory///PointingToDeclaration/"></a>[common]  <br>Content  <br>data class [NDFeedbackCategory](-n-d-feedback-category/index.md)(**categoryId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **displayName**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br>More info  <br>This class represents an individual event feedback category  <br><br><br>
| <a name="com.netradyne.driverisdk.eventFeedback/NDFeedbackConversation///PointingToDeclaration/"></a>[NDFeedbackConversation](-n-d-feedback-conversation/index.md)| <a name="com.netradyne.driverisdk.eventFeedback/NDFeedbackConversation///PointingToDeclaration/"></a>[common]  <br>Content  <br>data class [NDFeedbackConversation](-n-d-feedback-conversation/index.md)(**image**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **userId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **timestamp**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))  <br>More info  <br>This class represents a single conversation between Driver and ND support for a event feedback submitted by Driver.  <br><br><br>
| <a name="com.netradyne.driverisdk.eventFeedback/NDFeedbackState///PointingToDeclaration/"></a>[NDFeedbackState](-n-d-feedback-state/index.md)| <a name="com.netradyne.driverisdk.eventFeedback/NDFeedbackState///PointingToDeclaration/"></a>[common]  <br>Content  <br>data class [NDFeedbackState](-n-d-feedback-state/index.md)(**feedbackMessageState**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **categoryDisplayName**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **feedbackId**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **categoryId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))  <br>More info  <br>Feedback state of a particular feedback category.  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| <a name="com.netradyne.driverisdk.eventFeedback//toJSONString/kotlin.collections.List[com.netradyne.driverisdk.eventFeedback.NDFeedbackCategory]#/PointingToDeclaration/"></a>[toJSONString](to-j-s-o-n-string.md)| <a name="com.netradyne.driverisdk.eventFeedback//toJSONString/kotlin.collections.List[com.netradyne.driverisdk.eventFeedback.NDFeedbackCategory]#/PointingToDeclaration/"></a>[common]  <br>Content  <br>fun [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[NDFeedbackCategory](-n-d-feedback-category/index.md)>.[toJSONString](to-j-s-o-n-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br>More info  <br>Get a JSON string representation of a list of [NDFeedbackCategory](-n-d-feedback-category/index.md)  <br><br><br>[common]  <br>Content  <br>fun [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[NDFeedbackConversation](-n-d-feedback-conversation/index.md)>.[toJSONString](to-j-s-o-n-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br>More info  <br>Get a JSON string representation of a list of [NDFeedbackConversation](-n-d-feedback-conversation/index.md)  <br><br><br>[common]  <br>Content  <br>fun [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[NDFeedbackState](-n-d-feedback-state/index.md)>.[toJSONString](to-j-s-o-n-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br>More info  <br>Get a JSON string representation of a list of [NDFeedbackState](-n-d-feedback-state/index.md)  <br><br><br>

