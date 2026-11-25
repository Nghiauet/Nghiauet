# Hi, I'm Nghia 👋

AI engineer in Vietnam. I build data tools for the Vietnamese market, run my own home server,
and contribute fixes and Vietnamese language support to the open-source tools I use every day.

## Now

- **Vietnamese voice control for Home Assistant.** Vietnamese had no active contributor since 2024.
  My first Vietnamese intent is merged in [OHF-Voice/intents](https://github.com/OHF-Voice/intents), and I'm adding the rest
  so you can run a smart home in Vietnamese.
- **Fixing bugs I hit in my own logs.** Small, tested patches to the integrations I run
  (Home Assistant `xiaomi_miio`, Ollama).
- **Kaggle:** [Competitions Expert](https://www.kaggle.com/phnghiapro), 2 silver medals.

## Projects

| Project | What it does |
| --- | --- |
| [finance-news-scraper](https://github.com/Nghiauet/finance-news-scraper) | Vietnamese finance news → structured data (FastAPI, Redis, LLM extraction) |
| [finance-ssc-scraper](https://github.com/Nghiauet/finance-ssc-scraper) | Financial reports from Vietnam's SSC → PostgreSQL |
| [GPU-monitor](https://github.com/Nghiauet/GPU-monitor) | `nvidia-smi` across many servers over SSH → SQLite → React dashboard |
| [angi](https://github.com/Nghiauet/angi) | *Hôm nay ăn gì?* A sassy lunch picker on a self-hosted LLM (Ollama, FastAPI) · [live](https://angi.wakeuplate.io.vn/) |

## Open-source contributions

In review:

- [OHF-Voice/intents#4362](https://github.com/OHF-Voice/intents/pull/4362): fix the Vietnamese skip words so "giúp tôi" / "cho tôi" are understood
- [home-assistant/core#194441](https://github.com/home-assistant/core/pull/194441): xiaomi_miio: treat network errors as "unavailable" instead of logging a traceback every poll
- [Kaggle/kaggle-cli#1258](https://github.com/Kaggle/kaggle-cli/pull/1258): fix the broken `competitions pages` command
- [n8n-io/n8n-docs#5815](https://github.com/n8n-io/n8n-docs/pull/5815): correct the Telegram Send Message Parse Mode default in the docs

Merged:

- [OHF-Voice/intents#4359](https://github.com/OHF-Voice/intents/pull/4359): Vietnamese sentences for setting fan speed (Home Assistant voice)
- [home-assistant/core#194082](https://github.com/home-assistant/core/pull/194082): mark the xiaomi_miio vacuum action fields as required
- [tranhuuhuy297/cliccy#5](https://github.com/tranhuuhuy297/cliccy/pull/5): faster hotkey handling through socket IPC (Rust)
- [openai/openai-cookbook#912](https://github.com/openai/openai-cookbook/pull/912): migrated the streaming notebook to the openai 1.x SDK
- [docker/docs#16426](https://github.com/docker/docs/pull/16426): corrected the `docker compose` command in the docs

Reviewed (merged):

- [home-assistant/core#193320](https://github.com/home-assistant/core/pull/193320): Telegram bot `chat_action` field marked required
- [home-assistant/core#193437](https://github.com/home-assistant/core/pull/193437): lazy discover for the Xiaomi Air Purifier 3H

Bugs reported (fixed upstream):

- [router-for-me/CLIProxyAPI#8012](https://github.com/router-for-me/CLIProxyAPI/issues/8012): `gpt-6.1-terra` was listed for Codex Free logins but the backend rejected it; fixed in [5b857ec](https://github.com/router-for-me/CLIProxyAPI/commit/5b857eccbf9e793f34caa910ae55ce4fa66a1057)

## Stack

Python (FastAPI, PyTorch) · TypeScript / Next.js · Go · Docker · PostgreSQL · Nginx · self-hosting on Linux

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/deptraicucmanh/)
