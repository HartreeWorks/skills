# Claude Code Skills

A collection of public skills for [Claude Code](https://claude.com/claude-code).

## Installation

To install a skill, clone it into your Claude Code skills directory:

```bash
git clone https://github.com/HartreeWorks/claude-skill--{skill-name}.git ~/.claude/skills/{skill-name}
```

Then restart Claude Code to load the skill.

## Available skills

### transcribe-audio

Transcribe audio files using Parakeet MLX. Internal skill used by youtube-transcribe and transcribe-call. Can also be invoked directly with "transcribe [audio file path]" or "transcribe this audio".

```bash
git clone https://github.com/HartreeWorks/claude-skill--transcribe-audio.git ~/.claude/skills/transcribe-audio
```

---

### youtube-transcribe

Transcribe YouTube videos using Parakeet MLX. Use when the user says "transcribe", "transcript", "transcription" with a YouTube URL, or asks to "get the text from this video", "what does this video say", or wants subtitles/captions from a YouTube video.

```bash
git clone https://github.com/HartreeWorks/claude-skill--youtube-transcribe.git ~/.claude/skills/youtube-transcribe
```

---

### youtube-download

Download videos and audio from YouTube using yt-dlp. Triggers on patterns like "dl https://youtube.com/..." or "download youtube".

```bash
git clone https://github.com/HartreeWorks/claude-skill--youtube-download.git ~/.claude/skills/youtube-download
```

---

### project-management

Manage non-coding projects (client work, personal projects, planning) with full scaffolding, Google Docs integration, and memory tracking.

```bash
git clone https://github.com/HartreeWorks/claude-skill--project-management.git ~/.claude/skills/project-management
```

---

### schedule-task

Manage macOS launchd LaunchAgents for scheduled command execution. Use for scheduling Claude commands to run daily, setting up cron-like jobs, or managing scheduled tasks.

```bash
git clone https://github.com/HartreeWorks/claude-skill--schedule-task.git ~/.claude/skills/schedule-task
```

---

### slack

Send and read Slack messages, check notifications, generate activity digests, and search message history via a Python client.

```bash
git clone https://github.com/HartreeWorks/claude-skill--slack.git ~/.claude/skills/slack
```

---

### secure-mcp-install

Security-focused workflow to clone, audit, and install MCP servers at pinned commits with automatic updates disabled.

```bash
git clone https://github.com/HartreeWorks/claude-skill--secure-mcp-install.git ~/.claude/skills/secure-mcp-install
```

---

## About

These skills are maintained by [HartreeWorks](https://github.com/HartreeWorks). Each skill repository follows the naming convention `claude-skill--{skill-name}`.

For more information about Claude Code skills, see the [Claude Code documentation](https://docs.anthropic.com/en/docs/claude-code).
