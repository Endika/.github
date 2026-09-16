# Security policy

This policy covers every public repository under [@Endika](https://github.com/Endika)
that does not define its own.

## Reporting a vulnerability

Open the repository's **Security** tab and click **Report a vulnerability**. That starts a
private thread that only you and I can read. Please don't use a public issue for a security
problem.

Useful things to include: what the problem is, how to reproduce it, and what someone gets
out of exploiting it. A short proof of concept beats a scanner report.

## What to expect

These are personal projects and I maintain them alone, so I can't commit to a response
time. I do read every report, and I'll tell you whether I'm fixing it and roughly when.
If you'd rather not wait on me, you're free to disclose publicly — just say so in the
thread first.

When a fix ships I publish the advisory from the repository, and you're credited unless
you ask me not to.

## Scope

The latest released or deployed version of each project. Older tags and abandoned branches
are out of scope.

Most of these are offline-first PWAs that keep their data in the browser; a few talk to a
Supabase backend. Bugs in third-party dependencies are better reported upstream, but tell
me anyway if one of my projects is exposed through it.
