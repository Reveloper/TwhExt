# Getting start

## Step by step configure _TonHub extension_ for your app

* Create [Remote](doc:tonhub-remote-connector) connector.
* Create session via [connector](/docs/tonhub-remote-connector#creating-a-connector).
* Get instalation link for your app from Link Generator. 
* Create [Local](doc:tonhub-local-connector) connector for operations when running as extension.
* Add the necessary meta tags into your app's head section
* Use session for request [transactions](/docs/tonhub-remote-connector#requesting-transaction) or [signatures](/docs/tonhub-remote-connector#requesting-signature).




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
