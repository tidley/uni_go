# UniGo

# Background

Case study of WeChat's ecosystem and how to implement using decentralised technologies in Rust.

# Aim

- Research the components in WeChat (messaging, payments, blogging, meeting)
- Create decentralised app which interacts with tech that offers sufficient performance. E.g. messaging that must deliver messages whilst you were offline, so check past events when eventually going online and use events as notifier of new messages in real-time. Sender must therefore pay tx fee.

## WeChat Components
ref: https://en.wikipedia.org/wiki/WeChat
- instant messaging
    - text
    - hold-to-talk voice messaging
    - broadcast (one-to-many)
    - video conferencing
    - photo and video sharing
    - location sharing
    - message recall
- social media
- mobile payment
- gaming

# Tasks

## 1. Develop phone app to interact with Polygon
### Goals:
1. Upload data to IPFS and store CID in Polygon transaction metadata
1. View live data and historic messages (event-notifier)

### Sub-tasks
- [ ] Build Flutter app with Rust bindings
- [ ] Build Rust-Polygon interactions

### Refs:
https://pub.dev/packages/flutter_rust_bridge

# Examples

## Rust Chat app
https://www.youtube.com/watch?v=NS9Dh63i_Q4
https://github.com/tidley/chat-app
