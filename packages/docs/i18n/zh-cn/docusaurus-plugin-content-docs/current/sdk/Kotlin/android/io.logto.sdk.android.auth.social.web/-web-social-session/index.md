# WebSocialSession


class WebSocialSession(val context: [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html), val redirectTo: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val callbackUri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val completion: [Completion](../../io.logto.sdk.android.completion/-completion/index.md)&lt;[SocialException](../../io.logto.sdk.android.auth.social/-social-exception/index.md), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;) : [SocialSession](../../io.logto.sdk.android.auth.social/-social-session/index.md)

## Constructors

| 名称 | 概要 |
|---|---|
| WebSocialSession | fun WebSocialSession(context: [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html), redirectTo: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), callbackUri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), completion: [Completion](../../io.logto.sdk.android.completion/-completion/index.md)&lt;[SocialException](../../io.logto.sdk.android.auth.social/-social-exception/index.md), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;) |

## Functions

| 名称 | 概要 |
|---|---|
| handleResult | fun handleResult(data: [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)) |
| start | open override fun start() |

## Properties

| 名称 | 概要 |
|---|---|
| callbackUri | open override val callbackUri: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| completion | open override val completion: [Completion](../../io.logto.sdk.android.completion/-completion/index.md)&lt;[SocialException](../../io.logto.sdk.android.auth.social/-social-exception/index.md), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| context | open override val context: [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html) |
| redirectTo | open override val redirectTo: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |