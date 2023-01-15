---
title: Storify
description:
toc: true
authors:
  - gyeongmin-lee
tags: []
categories:
  - Projects
series: []
date: 2023-01-14T16:08:17-08:00
lastmod: 2023-01-14T16:08:17-08:00
featuredVideo:
featuredImage: /storify_project.png
draft: false
---

Cross-platform mobile application that lets users add captions to songs on Spotify.

<!--more-->

## Links

- <a href="https://play.google.com/store/apps/details?id=com.minlee.storify&pli=1" target="_blank">Play Store</a>
- App Store - To be launched
- <a href="https://github.com/gyeongmin-lee/Storify" target="_blank">GitHub</a>
- <a href="https://www.figma.com/file/zVlDPaq62mBlO42UqvBGZh/Storify?node-id=0%3A1&t=v6PFtGH8VsHBoBs1-1" target="_blank">Figma Mockup</a>

## How It Was Built

I built this application in the summer of 2020 during my summer break at BCIT. I have always enjoyed listening to music, but what I found to be even more enjoyable was writing about special memories, feelings, or reviews on songs, as well as reading about other people's unique stories on some of my favorite songs. This led me to the idea of creating a platform where users could write and share their stories about their favorite tracks.

I used Figma to visualize my rough idea in my head and created a mockup in Figma with possible user flows, which helped me to have a clear understanding of the design and user experience. I also used it to test the usability and get feedback from peers.

This was my first project using Flutter, but I found the framework to be easy to pick up as I already had experiences with React. The two most challenging parts of building the app were state management and real-time tracking of the "Now Playing" song in Spotify. For state management, I used `flutter_block` package to create a robust state management system, and used a method of polling with `rx_dart` package to subscribe to the user's action in Spotify.

As this was the first time launching a user-facing service, I didn't have much expectation. I would have been satisfied if there was one user who had the same needs as me and achieved the goal of adding a special story to their playlist. But to my surprise, the app now has over 5,000 downloads, and it's great to be able to browse other people's special memories or reviews on their favorite tracks! I have more ideas for the app but haven't had a chance to revisit it yet. My goal is to launch an iOS version of the app with more features in the future, to reach more users and make their experience even better.

## Features

- Sign in using Spotify
- Load playlists from Spotify
- Add captions to each song in a Spotify playlist
- Share playlist via link
- Browse playlists created by other users
- Save playlists

## Built With

- <a href="https://flutter.dev/" target="_blank">Flutter</a>
- <a href="https://cloud.google.com/firestore/docs/client/get-firebase" target="_blank">Google Firebase</a>

## Stats

- 30+ stars and 10+ forks on GitHub
- 5K+ downloads on Play Store
