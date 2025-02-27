# Okta Sign-In Widget Customization Example

This repo contains the completed [HTML and CSS code](CustomOktaSign-InWidget.html) in the tutorial [From Meh to Wow: Customize Your Okta Sign-In Experience](https://developer.okta.com/blog/2025/02/26/okta-hosted-sign-in-widget).

**Prerequisites**
This guide assumes you already have:
- A Single Sign-On (SSO) application that redirects to Okta for authentication.
- A customized Okta Hosted Sign-In Widget with a [custom domain](https://help.okta.com/en-us/content/topics/settings/settings-configure-custom-url.htm) enabled to make the necessary edits that I will demonstrate in this tutorial.
- This tutorial uses the Sign-In Widget **version ^7**.
- [Self-Service Registration (SSR)](https://support.okta.com/help/s/article/sign-up-link-missing-from-okta-login-page-during-sp-initiated-login?language=en_US) enabled to handle user self-registration.

If you don't have the above setup just yet, you can test one of our [samples](https://github.com/okta-samples) with a free Developer Edition Account under [Sign up free for Developer Edition](https://developer.okta.com/signup/). 

>**Note:** You must use your work email address to sign up for a free developer account.

Within the samples, please refer to the ones labeled **Okta Hosted Login** or **Redirect Model**. For example, here is one in [React](https://github.com/okta-samples/okta-react-sample) and [Angular](https://github.com/okta-samples/okta-angular-quickstart). Each sample readme should have directions on creating an SSO application within Okta. Still, for more info, you can always refer to this page on [creating app integrations](https://help.okta.com/en-us/content/topics/apps/apps_app_integration_wizard_oidc.htm.). One last note, be sure you are using the correct authorization server for SSO and that is the [Okta Org Authorization Server](https://developer.okta.com/docs/concepts/auth-servers/#org-authorization-server). 

For even more examples of how to get started with the Okta Sign-In Widget, check out this [post](https://developer.okta.com/blog/2023/01/12/signin-custom-domain), which walks you through the basic customizations and setting up a custom domain.

## Help

Please post any questions as comments on the [blog post](https://developer.okta.com/blog/2025-02-26-okta-hosted-sign-in-widget), or visit our [Okta Developer Forums](https://devforum.okta.com/).

## License

Apache 2.0, see [LICENSE](LICENSE).

[blog]: https://developer.okta.com/blog/
