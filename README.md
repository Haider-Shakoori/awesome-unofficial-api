# Awesome Unofficial Messengers APIs & Reverse-Engineered Clients

A curated collection of **unofficial**, **reverse-engineered**, **private/user-level API** libraries, clients, userbots, hosted services, and bridges for major messengers.

**⚠️ Important Disclaimer**  
- These projects/services usually violate the platform's Terms of Service.  
- High risk of account bans, sudden protocol breaks, or legal issues.  
- Most are maintained sporadically (or are commercial hosted services) — always check status, reviews, last updates, and risks.  
- Use responsibly, ideally only for personal/educational/research purposes.

## WhatsApp

WhatsApp's multi-device protocol (WhatsApp Web style) is one of the most actively reversed/hosted.

- **Baileys**  
  Lightweight, multi-device WhatsApp Web API (TypeScript/Node.js, no browser automation)  
  https://github.com/WhiskeySockets/Baileys

- **whatsmeow**  
  High-performance Go library implementing the multi-device protocol  
  https://github.com/tulir/whatsmeow

- **WAHA**  
  WhatsApp HTTP API server with multiple backends (WEBJS, NOWEB, GoWS)  
  https://github.com/devlikeapro/waha

- **Evolution API**  
  Ready-to-deploy REST API wrapper/server for WhatsApp (multi-engine support)  
  https://github.com/EvolutionAPI/evolution-api

- **WaSenderAPI** (hosted service)  
  Affordable unofficial WhatsApp API platform (hosted, with SDKs for Node.js/Python/Laravel). Supports unlimited messaging, multi-sessions, webhooks, real-time events, various message types (text/media/contacts/location). No Meta approval needed; starts at $6/month. Uses your own WhatsApp sessions (Web protocol emulation).  
  Website: https://wasenderapi.com/  
  Docs: https://wasenderapi.com/api-docs  
  SDKs: npm (wasenderapi), PyPI (wasenderapi), Packagist (wasenderapi/wasenderapi-laravel)

- **RelayWA** (hosted service)  
  Unofficial WhatsApp Web API using QR-linked sessions, with REST endpoints, webhooks, and multi-session management. SDKs for JavaScript/TypeScript, Python, PHP, and .NET. Not affiliated with Meta or WhatsApp.  
  Website: https://relaywa.com  
  Docs: https://relaywa.com/api-docs  
  SDKs: [npm](https://www.npmjs.com/package/@relaywa/sdk), [PyPI](https://pypi.org/project/relaywa-sdk/), [Packagist](https://packagist.org/packages/relaywa/sdk), [NuGet](https://www.nuget.org/packages/RelayWA.Sdk/0.1.1)

- **mautrix/whatsapp**  
  Matrix puppeting bridge (connect WhatsApp to Matrix ecosystem)  
  https://github.com/mautrix/whatsapp

## Telegram

Telegram's MTProto (user/client protocol) is well-documented unofficially and has excellent libraries.

- **Telethon**  
  Popular asyncio-based Python MTProto client (great for userbots)  
  https://github.com/LonamiWebs/Telethon

- **Pyrogram**  
  Modern, elegant Python MTProto framework  
  https://github.com/pyrogram/pyrogram

- **WTelegramClient**  
  Full-featured MTProto client in C# / .NET  
  https://github.com/wiz0u/WTelegramClient

- **gotd/td**  
  High-performance Go implementation of MTProto  
  https://github.com/gotd/td

## Signal

Signal is highly secure and aggressively fights unofficial clients → few stable options remain.

- **signald**  
  Daemon with REST/JSON-RPC/dbus interface (most used for bridging)  
  https://gitlab.com/signald/signald

- **signal-cli**  
  Java-based CLI + REST daemon (unofficial, widely used)  
  https://github.com/AsamK/signal-cli

- **libsignal**  
  Official crypto library (Rust), but not a full client/protocol reverse  
  https://github.com/signalapp/libsignal

## KakaoTalk

Very closed Korean messenger; mostly automation via bridges or UI/DB hooks.

- **remote-kakao**  
  Node.js bridge for bot creation via MessengerBot (UDP-based)  
  https://github.com/remote-kakao/core

- **kakaocli**  
  CLI client using UI/DB automation (Mac-focused)  
  https://github.com/silver-flight-group/kakaocli

## LINE

Official Messaging API exists for Official Accounts, but full user-level reverses are mostly dead after protocol changes.

- Legacy Thrift-based reverses (2015–2020 era, mostly read-only/broken now)  
  https://github.com/ruyaoyao/LINE-instant-messenger-protocol  
  https://github.com/bobwei/Line-Unofficial-API

Living full RE clients are rare in 2026.

## WeChat / Weixin

Extremely closed; public reverses die quickly due to aggressive enforcement.

- **wechat-dump**  
  Tools for dumping chat history (Android rooted/analysis focused)  
  https://github.com/ppwwyyxx/wechat-dump (and active forks)

- **wxhelper**  
  Hook/injection-based reverse for WeChat (popular in China)  
  https://github.com/ttttupup/wxhelper

- Research/protocol analysis  
  Citizen Lab WeChat reports and dumps  
  https://github.com/citizenlab/wechat-security-report

## Twitter / X (Undocumented / Internal APIs)

Special section for Twitter/X, as it has a vibrant ecosystem of reverse-engineered GraphQL/internal endpoints (often used for clients, scrapers, feature unlocks).

- **AwesomeTwitterUndocumentedAPI**  
  Curated list of awesome Twitter Undocumented API resources: implementations (TypeScript/Python/Dart), documentation, tools (OpenAPI specs, feature flag editors), applications (old TweetDeck restore, tweet archiving), and deprecated projects. Focuses heavily on GraphQL-based internal APIs.  
  https://github.com/fa0311/AwesomeTwitterUndocumentedAPI

## Multi-Messenger / Bridge Projects

- **mautrix** organization  
  Bridges for WhatsApp, Telegram, Signal, Discord, etc. to Matrix  
  https://github.com/mautrix

- **reversing-unofficial-APIs**  
  General resources/guides for reversing unofficial APIs (mobile/web)  
  https://github.com/ropcat/reversing-unofficial-APIs

## Related Awesome Lists & Resources

- **awesome-reverse-engineering**  
  Broad list of RE tools (includes mobile/protocol stuff)  
  https://github.com/alphaSeclab/awesome-reverse-engineering

- **whatsapp-web-reveng**  
  Classic breakdown of WhatsApp Web protocol (2017, still educational)  
  https://github.com/sigalor/whatsapp-web-reveng

## Contributing

Found an active 2025–2026 project? Submit a PR!  
Especially welcome: updates for Asian messengers (KakaoTalk, LINE, WeChat), new multi-device implementations, Twitter/X internals, or any dead-project alternatives.

License: CC0 (public domain), but respect each linked project's license.

<small>  
awesome list, unofficial api, reverse engineered, private api, userbot, multi-device, whatsapp reverse, telegram mtproto, signal unofficial, kakaotalk reverse, line protocol, wechat reverse, twitter undocumented api, x graphql api, messaging api reverse engineering  
</small>
