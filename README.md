<img src="logo/logo.svg" alt="Mark My Words logo" width="96" height="96" align="left">

# Mark My Words — a VRG app

Six dials per person on a radar you drag, plus a note. It turns them into a short brief, so you,
or your AI, write to each person the way they like to be written to.

Which six dials depends on who the person is to you. Pick one of seven sets when you add them:

| Set | The six dials |
|---|---|
| Colleagues | Friendly · Tech savvy · Busy · Hierarchy · Handholding · Delegation |
| Clients and customers | Warmth · Formality · Patience · Detail wanted · Reassurance needed · Decision speed |
| Investors and board | Brevity · Numbers first · Risk appetite · Formality · Proof needed · Update frequency |
| Team you lead | Autonomy · Directness · Encouragement · Pace · Structure · Feedback frequency |
| Suppliers and partners | Firmness · Warmth · Formality · Speed · Written record · Flexibility |
| Friends and family | Humour · Emotion · Directness · Brevity · Emoji and slang · Formality |
| Public and audience | Expertise level · Attention span · Humour · Authority · Call to action · Formality |

Local-first: no sign-in, no server, no telemetry. Your data stays in your browser and in a JSON
file you export and own.

**Status: v0.2 is out.**

- **Try it:** https://vrgli.github.io/mark-my-words/
- **Download:** the zip on the [Releases](https://github.com/vrgli/mark-my-words/releases) page

## Use it

Open `index.html` in a browser, or use the link above. That is all. Nothing to install, nothing
to build. Add a person, pick the set that fits them, drag the yellow dots on the radar (or use the
sliders), and copy the brief for your AI. **Export JSON** saves everyone to a file; **Import JSON**
brings them back.

You can change someone's set later. Because the six dials are different, the app warns you first
and then starts all six at 5 again: nothing is carried over. People saved with v0.1, in the browser
or in an exported file, open as **Colleagues** with their values intact.

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
