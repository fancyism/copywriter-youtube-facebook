# copywriter-youtube-facebook

Agent skill — แปลง transcript/summary เป็นโพสต์ Facebook ภาษาไทย "พร้อมโพสต์ทันที"

## ทำอะไร / What it does

เขียนโพสต์ FB จากข้อมูลจริงที่ผู้ใช้ให้เท่านั้น (กฎ no-hallucination เข้ม) โครง Hook → Expand → Break expectation → Insight → Takeaway → CTA อ่านแล้วเหมือนคนจริงเขียน ไม่ใช้ emoji ไม่ใช้คำกลาง ๆ

## ใช้เมื่อไหร่ / When to use

"เขียนโพสต์ Facebook/แปลง transcript เป็นโพสต์/โพสต์จากคลิปนี้" หรือต้องการคอนเทนต์ไทยสำหรับ FB feed

## ติดตั้ง / Install

ใช้ได้กับ agent ที่รองรับ skills (Claude Code, Codex, OpenCode, ฯลฯ):

```bash
npx skills add kanomwhandev/copywriter-youtube-facebook
```

หรือคัดลอกโฟลเดอร์นี้ไปไว้ใน skill directory ของ agent คุณ (เช่น `~/.claude/skills/` หรือ `~/.agents/skills/`) แล้วเปิด session ใหม่


## License

[MIT](./LICENSE) — © 2026 Affan Samaeng
