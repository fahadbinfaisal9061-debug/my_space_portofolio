# MY SPACE V2 — Personal Portfolio

## Open locally
1. Extract the ZIP.
2. Open `my_space_portfolio/index.html` in a modern browser.

## Secret keyboard access
- Windows / Linux: press **Ctrl + Shift + M** together.
- macOS: press **Cmd + Shift + M** together.
- The shortcut does not run while focus is inside an input, textarea, select, or editable text field.
- Clicking the MY SPACE logo does not open the secret interface. The logo is an ordinary link to the top of the public homepage.
- A single key press or any other click does not open the secret interface.

On first use, the login screen asks you to create a passcode of at least 6 characters. Later visits ask for that passcode.

## Private dashboard features
- Official Instagram Direct inbox: https://www.instagram.com/direct/inbox/
- Add and remove Instagram friend usernames (opens their real Instagram profiles).
- Private notes saved in this browser.
- Quick Instagram links.
- Lock & Exit / Back to Portfolio.

Instagram sign-in and messaging happen on Instagram itself. This website does not collect your Instagram password, read DMs, or simulate Instagram messaging.

## Important security limitation
This ZIP is a static front-end website. Its passcode check, dashboard visibility, friend shortcuts, and notes are handled in the browser. This is a convenience gate, **not real security**: someone with access to browser developer tools or the browser profile can bypass the gate or inspect/change local browser storage. Do not store highly sensitive information here or publish it as a genuinely protected private area.

For real protection, deploy a backend with server-side authentication, secure sessions, authorization checks on every private request, and protected server-side storage. A static HTML-only ZIP cannot provide that by itself.

## Public portfolio
The existing MY SPACE homepage content, layout, animations, typography, and red/yellow/orange colour palette have been retained. The V2 changes are limited to secret access and its login styling/keyboard behaviour.

## Personalize
Edit `index.html`:
- Replace `MY SPACE` with your chosen website name.
- Replace `HELLO, I'M YOU.` and the About text with your details.
- Replace the sample project cards with your work.
- Change `hello@example.com` to your email.
