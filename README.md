# 2D Dungeon Crawler - Anas' Abyss of Shadows

A 2D dungeon crawler survival game built in Python using Pygame, developed solo as my A-Level Computer Science NEA (Non-Exam Assessment) project.

## About This Project

Designed and built end-to-end, applying object-oriented programming principles throughout. Covers the full development lifecycle, from initial requirements gathering and design through to implementation and testing

## Features
Wave-based survival gameplay, enemies increase in number each wave
Multiple enemy types with different behaviours (melee chasers, ranged shooters)
Player movement, shooting, and animation states (idle/running, directional flipping)
Health packs and temporary power-ups (rapid fire, enemy freeze)
User authentication (login / create account)
Persistent leaderboard, backed by an integrated SQLite database
Player stat search using a binary search algorithm across sorted usernames
Pause menu, controls screen, and game-over state

## Tech Stack
Language: Python
Library: Pygame
Database: SQLite
Local Setup
bash
git clone <repo-url>
cd dungeon-crawler
pip install pygame
python main.py
