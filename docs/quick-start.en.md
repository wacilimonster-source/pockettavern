# PocketTavern quick start

[Back to the README](../README.en.md) · [中文指南](quick-start.md)

## Install and update

Download `pocket_tavern_VERSION.apk` from **Assets** on the [latest release page](https://github.com/wacilimonster-source/pockettavern/releases/latest) and install it on Android. Updates can be installed over the current version. The update entry is **设置 → 通用 → 检查更新** (Settings → General → Check for updates).

## Remote mode

Prepare a running SillyTavern server accessible from your phone, with your characters and model service configured.

1. Open the server address in your phone's browser to confirm connectivity.
2. Enter the same address on PocketTavern's welcome screen and connect. A local-network example is `http://192.168.1.100:8000`; use your own server's address.
3. Open **角色** (Characters), select a character, then open a conversation or choose **新建对话** (New conversation).
4. Review the source, model, and configuration under **设置 → AI 服务** (Settings → AI service).
5. Send a message. Message controls provide editing, regeneration, continuation, and alternative response selection.

Remote-mode chat files are stored on your SillyTavern server.

## Local mode

Prepare access to a SillyTavern data source for the initial sync, plus credentials and an address for your chosen model service or gateway.

1. Choose **先在本机开一间** on the welcome screen to enter local mode. You can also switch modes in Settings.
2. Open **设置 → 远程数据源** (Settings → Remote data sources) and add your SillyTavern server. Previously connected servers can also be selected.
3. Open the data source, review the categories and differences, then select the characters, chats, world info, and configuration to sync to the phone. Review the displayed differences when replacing local data.
4. Open **设置 → AI 服务** and configure the source, address, API key, and model. For the gateway source, use its gateway configuration screen.
5. Return to **角色**, select a synced character, then create or continue a conversation.

After syncing, local mode uses on-device data and sends generation requests directly to your configured model service. Revisit the data source to review and sync subsequent server changes.

## Find a setting

| Task | App label |
| --- | --- |
| Configure model access | 设置 → AI 服务 |
| Select or manage presets | 设置 → 预设 |
| Configure prompts and personas | 设置 → 提示词与人设 |
| Edit world info | 设置 → 世界书 |
| Change appearance | 设置 → 界面与显示 |
| Check the version or update | 设置 → 通用 |

## Troubleshooting

- **No characters** — check the current mode. In remote mode, check the server connection. In local mode, review the character sync results in Remote data sources.
- **Characters load but generation fails** — check the source, model, key, service address, and displayed error. Connectivity and usage limits depend on the model service.
- **A complex card behaves unexpectedly** — record the extension features and steps involved, and prepare a minimal example.
- **Need help** — open an [issue](https://github.com/wacilimonster-source/pockettavern/issues/new) with the app and Android versions, mode, steps, and screenshots. Remove credentials and private data before sharing.
