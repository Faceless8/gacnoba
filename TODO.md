# Fix: Old messages appearing in new chats (fetching old chat messages into new chat)

## Steps:
- [x] Verify project/repo state
- [x] Create TODO.md
- [ ] Install & auth gh CLI (winget executed, verify path)
- [x] Create branch blackboxai/fix-chat-messages-bug
- [x] Edit gacnoba/index.html with time filter fix
- [ ] git add .; git commit -m "fix: add created_at filter to prevent old messages in new chats"
- [ ] git push origin blackboxai/fix-chat-messages-bug
- [ ] gh pr create --title "Fix: Prevent old messages loading in new chats" --body "Filter messages by created_at > chat start time to avoid historical messages."


