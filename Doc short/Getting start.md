# Getting start

## Step by step configure _Tonhub extension_ for your application

1. Create [Remote connector](https://developers.tonhub.com/docs/tonhub-remote-connector).
2. Create [session](https://developers.tonhub.com/docs/tonhub-remote-connector#starting-a-new-session) via connector.
3. Get instalation link for your application from Tonhub [Link Generator](https://tonwhales.com/tools/link) or Sandbox [Link Generator](https://sandbox.tonwhales.com/tools/link). 
4. Create [Local connector](https://developers.tonhub.com/docs/tonhub-local-connector) for operations when running as extension.
5. Add the necessary [meta tags](https://github.com/Reveloper/TwhExt/edit/main/Doc%20short/Getting%20start.md#add-the-necessary-meta-tags-into-your-apps-head-section) into your app's head section
6. Use session for request [transactions](/docs/tonhub-remote-connector#requesting-transaction) or [signatures](/docs/tonhub-remote-connector#requesting-signature).




## Add the necessary meta tags into your app's head section

Configure your Tonhub extension's appearance using well-known tags: 
- Title
- Description 
- Logo 
- Icon 
- Theme color

```
<!DOCTYPE html>
<html lang="en">
    <title>Tonhub</title>
    <meta name="description" content="Tonhub - everyone on Toncoin"/>
    <meta name="theme-color" content="#2E3153"/>
    <meta name="application-name" content="Tonhub"/>
</html>
```
See [Metadata headers](doc:metadata-headers) section for more details. 

## Generate a URL link to your app as Tonhub extension

You can create links to your app as an Tonhub extension with [Tonhub Link Generator](doc:tonhub-link-generator). Also you can validate your metadata headers with this tool as it allows you to preview extension's: 
- Title
- Description
- Theme Color
- Logo/Icon image and generated from image blurhash show before Image has loaded 

<img width="919" alt="1 - gettingstarted" src="https://user-images.githubusercontent.com/39581753/178587512-df558e86-2746-4dd5-97c8-e7ad37d8c100.png">
