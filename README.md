# IncidentLab lab: Ghost in the Network

A Linux shell in your browser, with the investigation tools (tcpdump, dig, jq, GNU awk/grep/sed, git) and
the case's **public evidence** in `/case`. You type your answers on the IncidentLab site, as usual.

## Open it (free, on your own GitHub account)

1. Click **Use this template** → **Create a new repository**, with **your account** as the owner. It can be
   private.
2. In your new repository: **Code** → **Codespaces** → **Create codespace on main**.
3. When the terminal opens: `cd /case && less README_FIRST.txt`.

Open the Codespace from **your own copy**, not from this repository: then it uses your personal free
Codespaces quota (GitHub Free includes 120 core-hours a month; this lab uses the 2-core machine).
**Stop or delete the Codespace when you're done**, so it doesn't use your quota while idle.

## Or run it locally

```sh
docker run -it --rm ghcr.io/incidentslab/lab-ghost-in-the-network:v1
```

The image holds exactly the evidence zip you can download from the site, and nothing else: no answers, hints
or solutions. See [IncidentsLab/labs](https://github.com/IncidentsLab/labs) for how it's built and checked.
