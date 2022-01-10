# Planner

Lightweight, interactive planning tool that visualizes a series of tasks using an HTML canvas.

![Planner JS meta-image](https://user-images.githubusercontent.com/29597/148128667-3e2cd87a-3a7a-4123-bdbc-168965baa4e6.png)

Try it yourself at [plannerjs.dev](https://plannerjs.dev)

Plans created with Planner are automatically saved to the URL and can be easily shared with others.

If you like this project ☕️ buy me a cup of coffee at [patreon.com/bvaughn](https://www.patreon.com/bvaughn) 😃

---

## Examples

### [View years example](https://plannerjs.dev/?data=eyJ0YXNrcyI6W3sic3RhcnQiOiIyMDIyLTAxLTAxIiwic3RvcCI6IjIwMjItMTItMzEiLCJuYW1lIjoiMjAyMiIsIm93bmVyIjoiT3RoZXIgdGVhbSJ9LHsic3RhcnQiOiIyMDIyLTAxLTAxIiwic3RvcCI6IjIwMjItMDYtMzAiLCJuYW1lIjoiSDEgMjAyMiJ9LHsic3RhcnQiOiIyMDIyLTA3LTAxIiwic3RvcCI6IjIwMjItMTItMzEiLCJuYW1lIjoiSDIgMjAyMiJ9LHsic3RhcnQiOiIyMDIzLTAxLTAxIiwic3RvcCI6IjIwMjMtMDYtMzAiLCJuYW1lIjoiSDEgMjAyMyJ9XSwidGVhbSI6e319)

![Planner screenshot](https://user-images.githubusercontent.com/29597/148847931-204e6743-e3e9-448a-a5f9-94d84949833b.png)

### [View months example](https://plannerjs.dev/?data=eyJ0YXNrcyI6W3siaWQiOiJleGFtcGxlIiwibmFtZSI6IkRlc2lnbiBBUEkiLCJvd25lciI6ImJ2YXVnaG4iLCJzdGFydCI6IjIwMjItMDEtMDEiLCJzdG9wIjoiMjAyMi0wMy0xNSJ9LHsiaWQiOjIsIm5hbWUiOiJGaW5pc2ggcHJvamVjdCBjYXJyeW92ZXIiLCJvd25lciI6InN1c2FuIiwic3RhcnQiOiIyMDIyLTAxLTAxIiwic3RvcCI6IjIwMjItMDMtMDEifSx7ImlkIjowLCJuYW1lIjoiV3JpdGUgQVBJIGRvY3VtZW50YXRpb24iLCJvd25lciI6InN1c2FuIiwic3RhcnQiOiIyMDIyLTAzLTAxIiwic3RvcCI6IjIwMjItMDUtMDEiLCJkZXBlbmRlbmN5IjoiZXhhbXBsZSJ9LHsiaWQiOjMsIm5hbWUiOiJHaXRIdWIgaXNzdWUgc3VwcG9ydCIsIm93bmVyIjoidGVhbSIsInN0YXJ0IjoiMjAyMi0wMy0wMSIsInN0b3AiOiIyMDIyLTA0LTAxIiwiaXNPbmdvaW5nIjp0cnVlfSx7ImlkIjoxLCJuYW1lIjoiU3VwcG9ydCBwcm9kdWN0IHRlYW0gaW50ZWdyYXRpb24iLCJvd25lciI6ImJ2YXVnaG4iLCJzdGFydCI6IjIwMjItMDMtMTUiLCJzdG9wIjoiMjAyMi0wNS0xNSIsImlzT25nb2luZyI6dHJ1ZSwiZGVwZW5kZW5jeSI6ImV4YW1wbGUifV0sInRlYW0iOnsiYnZhdWdobiI6eyJhdmF0YXIiOm51bGwsIm5hbWUiOiJCcmlhbiJ9LCJ0ZWFtIjp7ImF2YXRhciI6bnVsbCwibmFtZSI6IlVuY2xhaW1lZCJ9fX0)

![Planner screenshot](https://user-images.githubusercontent.com/29597/148847915-e3089665-8939-4265-bb63-44c35a7d93d1.png)

### [View weeks example](https://plannerjs.dev/?data=eyJ0YXNrcyI6W3sibmFtZSI6IldlZWsgQSIsInN0YXJ0IjoiMjAyMi0wMS0wMyIsInN0b3AiOiIyMDIyLTAxLTA5Iiwib3duZXIiOiJFcmluIn0seyJuYW1lIjoiV2VlayBCIiwic3RhcnQiOiIyMDIyLTAxLTEwIiwic3RvcCI6IjIwMjItMDEtMjMiLCJvd25lciI6IkVyaW4ifSx7Im5hbWUiOiJXZWVrIEMiLCJzdGFydCI6IjIwMjItMDEtMTciLCJzdG9wIjoiMjAyMi0wMS0yMyIsIm93bmVyIjoiQ2hyaXMifV0sInRlYW0iOnt9fQ)

![Planner screenshot](https://user-images.githubusercontent.com/29597/148847895-213f4307-6d9b-497d-9b7a-9e6fb5dd9e85.png)

### [View days example](https://plannerjs.dev/?data=eyJ0YXNrcyI6W3sic3RhcnQiOiIyMDIyLTAyLTEyIiwic3RvcCI6IjIwMjItMDItMTMiLCJuYW1lIjoiU3ByaW5nIGNsZWFuaW5nIiwib3duZXIiOiJ0aW1lb2ZmIn0seyJzdGFydCI6IjIwMjItMDItMTQiLCJzdG9wIjoiMjAyMi0wMi0xNyIsIm5hbWUiOiJXb3JrIiwib3duZXIiOiJwcm8ifV0sInRlYW0iOnsicHJvIjp7Im5hbWUiOiJQcm9mZXNzaW9uYWwgQnJpYW4ifSwidGltZW9mZiI6eyJuYW1lIjoiVGltZSBvZmYgQnJpYW4ifX19)

![Planner screenshot](https://user-images.githubusercontent.com/29597/148847859-cace24e7-e25d-4149-b191-14f9209959b0.png)

---

## Converting legacy plans

Planner switched from [jsurl2](https://npmjs.com/package/jsurl2) to Base64 encoding due to URL parsing problems jsurl2 caused websites like Twitter. If you created a plan with using the old jsurl2 encoding, you can migrate to the new format at the URL below:

https://plannerjs.dev/api/convert?(your-data-here)