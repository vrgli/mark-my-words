<img src="logo/logo.svg" alt="Mark My Words logo" width="96" height="96" align="left">

# Mark My Words — a VRG app

Six dials per person on a radar you drag, plus a note. It turns them into a short brief, so you,
or your AI, write to each person the way they like to be written to.

Which six dials depends on who the person is to you. Pick one of seven sets when you add them,
and add more sets later: a colleague who is also a friend gets both, each with its own six dials.

| Set | The six dials |
|---|---|
| 👔 Colleagues | 😊 Friendly · 💻 Tech savvy · ⏱️ Busy · 🪜 Hierarchy · 🤲 Handholding · 📤 Delegation |
| 🤝 Clients and customers | ☀️ Warmth · 🎩 Formality · ⌛ Patience · 🔍 Detail wanted · 🛟 Reassurance needed · ⚡ Decision speed |
| 📈 Investors and board | ✂️ Brevity · 🔢 Numbers first · 🎲 Risk appetite · 🎩 Formality · 🧾 Proof needed · 🔄 Update frequency |
| 👥 Team you lead | 🪁 Autonomy · 🎯 Directness · 👏 Encouragement · 🏃 Pace · 🧱 Structure · 🔁 Feedback frequency |
| 📦 Suppliers and partners | ✊ Firmness · ☀️ Warmth · 🎩 Formality · ⚡ Speed · 📝 Written record · 🤸 Flexibility |
| ❤️ Friends and family | 😄 Humour · 💗 Emotion · 🎯 Directness · ✂️ Brevity · 🤙 Emoji and slang · 🎩 Formality |
| 📣 Public and audience | 🎓 Expertise level · 👀 Attention span · 😄 Humour · 🏛️ Authority · 👉 Call to action · 🎩 Formality |

Every set and every dial has its own icon, on the radar, on the sliders and in the brief you copy.

Local-first: no sign-in, no server, no telemetry. Your data stays in your browser and in a JSON
file you export and own.

**Status: v0.3 is out.**

- **Try it:** https://vrgli.github.io/mark-my-words/
- **Download:** the zip on the [Releases](https://github.com/vrgli/mark-my-words/releases) page

## Use it

Open `index.html` in a browser, or use the link above. That is all. Nothing to install, nothing
to build. Add a person, pick the set that fits them, drag the yellow dots on the radar (or use the
sliders), and copy the brief for your AI. **Export JSON** saves everyone to a file; **Import JSON**
brings them back.

A person can have several sets at once. Each set is a tab above the radar with its own six dials,
its own radar and its own sliders. **+ Add set** adds another of the seven (the sets they already
have are not touched); **Remove this set** drops one after a warning that its six values will be
lost. A person always keeps at least one set. The brief you copy covers every set the person has.
People saved with v0.1 or v0.2, in the browser or in an exported file, open with the one set they
had and their values intact.

## Fork it

Click **Fork** at the top of this page, clone your fork, edit `index.html`. Vanilla JS, one file,
zero dependencies.

## Logo

The Mark My Words mark lives in [`logo/`](logo/): `logo.svg` (source), `logo-512.png` and
`logo-128.png`. Near-black and VRG yellow, like everything else at vrg.li.

## Licence

MIT plus one condition, see [LICENSE.md](LICENSE.md): keep the visible "A VRG app" credit
linking to https://vrg.li (it is in the page footer).

A VRG app · https://vrg.li · more apps: https://github.com/vrgli/apps
