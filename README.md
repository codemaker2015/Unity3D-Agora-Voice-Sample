# Unity3D Agora Voice Sample

The Unity3D Agora Voice Sample App is an open-source demo that will help you get voice chat integrated directly into your Unity3D game applications using the Agora Gaming SDK.

With this sample app, you can:

- Join / leave channel
- Chat with another user on the same channel
- Mute audio input

## Screenshots

<img src="Demos/Screenshot.jpg" width="309px" height="635px" />

## Running the App
First, create a developer account at [Agora.io](https://dashboard.agora.io/signin/), and obtain an App ID. 

Clone this repo.  Note that you will see compiler errors before you download the SDK package.

Next, download the **Agora Voice SDK**.  There are two options in doing so.

**Option 1:** [Unity Asset Store](https://assetstore.unity.com/packages/tools/audio/agora-voice-sdk-for-unity-134505).

**Option 2:** Get the zipped SDK from [Agora.io SDK](https://docs.agora.io/en/All/downloads?platform=Unity). Unzip the downloaded SDK package and

- copy files from **libs/Android/** in SDK to **Assets/AgoraEngine/Plugins/Android/AgoraAudioKit.plugin/libs/** in project
- copy files from **libs/iOS/** in SDK to **Assets/AgoraEngine/Plugins/iOS/** in project
- copy files from **libs/Scripts/AgoraGamingSDK/** in SDK to **Assets/AgoraEngine/Scripts/AgoraGamingSDK/** in project

Open project with Unity. And then open the **HelloUnity3D** scene from the Demo folder on Unity Editor.  Fill your App ID into the GameController object's field.

Hit play and you are now good to go!

## Developer Environment Requirements
* Unity 2019 LTS.
* Tested on Unity 2019.4.33f1.
