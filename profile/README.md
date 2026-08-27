<div align="center">

<img src="./alter-mark.svg" alt="" height="132">

<h1>Being known.</h1>

<p><b>A name you own and a record of what you actually did that pays you whenever it is read.</b></p>

<p>
<img src="https://img.shields.io/badge/~alter-identity%20infrastructure-C9A84C?style=flat-square" alt="" width="176" height="20">
<img src="https://img.shields.io/badge/MCP-live-C9A84C?style=flat-square" alt="" width="62" height="20">
<img src="https://img.shields.io/badge/spec-IETF%20draft-555?style=flat-square" alt="" width="100" height="20">
<img src="https://img.shields.io/badge/licence-Apache%202.0-555?style=flat-square" alt="" width="120" height="20">
</p>

<p>
<a href="#what-is-alter">What is ~alter?</a>
&nbsp;·&nbsp;
<a href="#install">Install</a>
&nbsp;·&nbsp;
<a href="#getting-on-the-rail">Getting on the rail</a>
</p>

</div>

## What is ~alter?

~alter is identity infrastructure. One name, `~yourname`, carries a record of
you that any service or agent speaking the protocol can read, and that record
was assembled out of what you have actually done.

An agent can act in your name and the record carries who allowed it. A stranger
can establish that you are real before the first message. A collective holds a
record on the same terms a person does, so a union, a club or a country vouches
for its own members on the same rail.

The record deepens while you work, because what gets read is the trail you leave
rather than a claim you make about yourself.

Checking that your handle exists is free and stays free. Reading further than
that costs the reader money, the money comes to you, and you say who's allowed
past which line. Cutting a reader off is one command, no form and no review.

None of this is an AI agent, and nothing here acts on your behalf. Agents are
clients that read identity on the rails ~alter provides.

<details><summary><b>I want to know more</b></summary><br><p>Your friends do not know you from a login. Neither does your family, or the people you work with, or your sports team. They know who you are from how you have shown up, over years. You may look and sound nothing like you did ten years ago and it is still you.</p><p>Software still asks the narrow question. A password at the login screen. A token in the app. Each one checks whether this is the right person, right now, at this exact spot, and then looks away. Everything in between is invisible to it, and that is almost all of your life. The AI tools made it worse, because one of them writes in your name now, and when somebody asks who allowed it, there is no answer anywhere on this machine.</p><p><b>One name, and the record under it is yours.</b> <code>~yourname</code> works at every tool that speaks the protocol, so nothing is set up twice and there is no key to paste, at any point. What is in the record was read from what you did, not typed into a box by you or guessed at by a model. You can cut off access to any of it with one command. No form, no review.</p><p><b>Being read pays you.</b> Anyone can check for free that your handle exists. Reading further, past the fact of you, costs the reader money, that money goes to you, and you decide who gets to read what. Collectives hold a record on the same terms, because it is one record at every scale and the same form holds you, your team, and your country. A union, a club, a trade body, or a group of people who have never met can vouch for their own members and be read the same way you are.</p><p><b>Threads are how you get somewhere.</b> A thread is something you are working towards. You take one on yourself, or ~Alter plants one from what it can already see, or a collective confers one on you. What gets read is the trail you leave while you are doing it, never a certificate at the end.</p><p>All of that is the short version of an argument set out properly, in eight chapters at <a href="https://truealter.com/origin">truealter.com/origin</a>. Its seventy-six predictions were each written so the data could come back and say no. Five of them did, and those five are still published alongside the rest.</p></details>

<details><summary><b>I want to check it myself</b></summary>

None of it needs taking on trust. Hand this to the AI you already use and
let it take you through in your own words.

```text
Go to truealter.com, find the genesis and the origin papers, and read all of
them. Then start a discussion with me in my own language, no jargon.

Ask me one question at a time and wait for my answer. Follow what I am curious
about, not the order the site is written in.

Do not only read the pages. Connect to their interface directly and call
get_started. That tells you where I am and what comes next, and we work the
rest of this from there.

If I have a ~handle I will give it to you. If I do not and I decide I want
one, set it up with me here.

What I want to understand is what ~Alter is, how it applies to me, and what it
means for everyone else. Find me somewhere in it, and not the version written
for people who work in technology. Find the life nearest mine and walk me
through it, including what it would cost me.

Try to prove them wrong. Go and find where they show their working, and if
something is unclear or does not hold up, say so.
```

</details>

## What is true-alter?

The organisation where those rails get built. Every repository below is one
surface onto the same record, and each one ships on its own so you install the
one you want rather than a platform. The command line is the front door and most
people never need another.

The record formats are open drafts at the IETF rather than a format we hold, so
somebody else's implementation reads and writes the same thing ours does.

## Install

```
npm install -g @truealter/cli
```

Node 20 or later. It puts one command, `alter`, on your path and keeps your
session in an encrypted store under your home directory. Nothing runs in the
background until you ask it to.

If you'd rather install nothing at all, paste this address into Claude Code,
Claude Desktop, Cursor, VS Code or any other MCP client, then sign in there.

```
https://mcp.truealter.com/api/v1/mcp
```

## Getting on the rail

### 1. Take a handle

```
alter register
```

Pick a `~handle`. No browser, no passkey ceremony and no form. You confirm
you're over 18 and accept the member terms, the terminal solves a proof-of-work
challenge instead of a bot check, and the handle is yours from then on.

### 2. Connect one thing you already do

```
alter discover
```

Connect one thing you already do. GitHub and Discord pair over OAuth. An
Obsidian vault pairs locally and the writing stays on your machine. One
connection is enough for the record to start reading you.

### 3. See what the record says so far

```
alter whoami
```

Your handle, your consent tier, and which streams currently feed the record.
Tier labels, never numeric scores. On a brand new handle this says very little,
which is the honest answer and the reason step 2 comes before it.

### 4. Put it in front of the tools you use

```
alter wire
```

Finds the MCP clients already installed, Claude Code, Cursor, Claude Desktop and
VS Code among them, and merges ~alter into each one's config. `alter unwire`
reverses every target it touched, deterministically.

### 5. Watch who reads you

```
alter queries
```

Who read you, what they paid, and what you earned. Free, because you're the
subject of your own audit log. Empty until somebody reads you.

<details><summary><h3>What's in the organisation</h3></summary>

Each repository here is one way into the same layer. On its own, none of them
shows you the whole of it.

| Repository | What it is |
|---|---|
| [runtime](https://github.com/true-alter/runtime) | The daemon that keeps a `~handle` known on your own machine, over a Unix socket, D-Bus and the command line. Published to PyPI as `alter-runtime`. |
| [sdk](https://github.com/true-alter/sdk) | The TypeScript client. Check somebody is known, read inferred traits and settle a paid read in USDC from your own code. Published to npm as `@truealter/sdk`. |
| [obsidian](https://github.com/true-alter/obsidian) | ~alter inside an Obsidian vault. What you write stays on your machine and only consented inferences ever leave it. |
| [homebrew-tap](https://github.com/true-alter/homebrew-tap) | The command line packaged for macOS and Linux. `brew install true-alter/tap/alter`. |
| [mcp-ollama](https://github.com/true-alter/mcp-ollama) | An MCP server over local Ollama models, for work that should never leave the machine. |

The command line itself ships from npm as
[`@truealter/cli`](https://www.npmjs.com/package/@truealter/cli). Substrate, the
rail that carries handles, agreements, attestations and settlement, isn't open
yet.

Documentation is at [truealter.com/docs](https://truealter.com/docs), and the
notes for people building against the rails are at
[truealter.com/build](https://truealter.com/build). An agent doesn't need to
read any of it, because the server announces itself through the
[well-known manifests](https://truealter.com/.well-known/mcp.json) and the
public MCP directories. The record formats are open
[IETF drafts](https://datatracker.ietf.org/doc/search/?name=draft-morrison&activedrafts=on),
so an implementation somebody else writes will work with this one.

</details>

<details><summary><h3>Why any of this exists</h3></summary>

For a century, personality and intelligence testing has been done to people
rather than with them. Soldiers were sorted. Job-seekers were ranked. Children
were scored. The mathematics was neutral. Who owned the output never was.

~alter is the other choice, and its founding position is a document called What
I Choose. It's published, and it's anchored on-chain, so nobody can quietly edit
it later. Read it, and the eight chapters that test it, at
[truealter.com/origin](https://truealter.com/origin).

The current version, v5, was anchored on 18 June 2026 on
[Arweave](https://gateway.irys.xyz/B2GhBJUA3WxbnqGSaf2GciyZHuS5rqXefyBvZPvY7bp5)
and on
[Base](https://basescan.org/tx/0x306a11409fadc6971eadfbef0ab5a06081b38ae33cd997e1e38fd9db8f54f0b7).
Both are public and checkable without asking anyone here.

</details>

<details><summary><h3>The protocols underneath it</h3></summary>

The record formats are open Internet-Drafts, so somebody else's implementation reads and writes the same records this one does without asking us. These are the drafts this repository actually rests on.

| Draft | What it specifies |
|---|---|
| [`mcp-dns-discovery`](https://datatracker.ietf.org/doc/draft-morrison-mcp-dns-discovery/) | The DNS records that publish a `~handle`, the server that answers for it, and the signed envelope bound to it. |
| [`consent-settlement`](https://datatracker.ietf.org/doc/draft-morrison-consent-settlement/) | Binding a paid read of somebody's identity to their own recorded consent, and settling part of that payment to them. |
| [`identity-accord`](https://datatracker.ietf.org/doc/draft-morrison-identity-accord/) | Two parties executing a bilateral agreement as a signed document any third party can verify. |
| [`org-alter-policy-provision`](https://datatracker.ietf.org/doc/draft-morrison-org-alter-policy-provision/) | How a runtime resolves an organisation's substrate at start-up and retrieves its policy stack. |

Eighteen drafts make up the whole stack. The rest are on the [IETF datatracker](https://datatracker.ietf.org/doc/search/?name=draft-morrison&activedrafts=on).

</details>

<details><summary><h3>Issues, security and licence</h3></summary>

Bugs and questions belong in the issues of the repository they concern. If
you're not sure which one, the [runtime](https://github.com/true-alter/runtime)
issues are the safest place to start.

Security reports go to
[security@truealter.com](mailto:security@truealter.com), never a public issue.
The policy is at [truealter.com/security](https://truealter.com/security).

Published artefacts are Apache-2.0 and carry their licence in-repo.

</details>

---

<div align="center">

<sub><b>~alter</b> is identity infrastructure. Your name is <code>~yourname</code> and claiming one is free.</sub>

<sub>
<a href="https://truealter.com">Website</a> &nbsp;·&nbsp;
<a href="https://truealter.com/docs">Docs</a> &nbsp;·&nbsp;
<a href="https://truealter.com/origin">The argument in eight chapters</a> &nbsp;·&nbsp;
<a href="https://datatracker.ietf.org/doc/search/?name=draft-morrison&activedrafts=on">The open specifications</a> &nbsp;·&nbsp;
<a href="https://github.com/true-alter">Every repository</a>
</sub>

</div>
