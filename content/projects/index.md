---
title: Projects
layout: projects
hide_footer: false

params:
  projects:
    - segfault:
        title: Forum Website
        description: A small forum website dedicated to programming topics. Users can create accounts, log in/out, create threads, and post comments. This project uses Node.js on the backend and React.js on the frontend.
        tech: TypeScript, Node, Express, React
        link: https://github.com/LeftySolara/segfault-backend
        image: "segfault.png"
    - pantomime:
        title: Pantomime - A TUI Music Player
        description: Pantomime is a TUI music player built with NCURSES. It connects to your local or remote MPD instance and allows you to control playback, browse your library, and modify your current playlist. It was inspired by other MPD clients such as ncmpc and ncmpcpp.
        tech: C, NCURSES, CMake, libmpdclient
        link: https://github.com/LeftySolara/pantomime-old
        image: "pantomime.png"
    - mpd-rpc:
        title: MPD Rich Presence for Discord
        description: This is a basic implementation of Discord Rich Presence for MPD. It detects the currently playing song in MPD and sets your Discord status to display the track information.
        tech: C, CMake, discord-rpc, libmpdclient
        link: https://github.com/LeftySolara/mpd-discord-rpc
        image: mpd-discord-rpc.png
    - pypong:
        title: PyPong
        description: PyPong is a recreation of the classic game Pong, but written in Python. The game allows you to play against a computer-controlled opponent and keeps score.
        tech: Python, PyGame
        link: https://github.com/LeftySolara/pypong
        image: pypong.gif
        last: true
---
