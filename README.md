# MusicServiceAPI

## Overview

A REST API for any Music-Service application. Supports two systems: profiles and songs. For the profile system, apps can call the API to create, remove, profiles and friend, follow other profiles. Apps can also like/unlike songs to add/remove it from their playlist. For the song system, apps can create, delete songs and query for songs by properties. The API uses 2 microservices to handle the 2 systems, providing extensibility to the API.

## Tech Stack

Java, Spring Boot, MongoDB, Neo4j

## Process

Utilizes the Java Spring Boot framework to create the API and the microservices. The MongoDB document database is used for the profiles and the Neo4j graph database is used for the songs and the mapping from profiles to songs (i.e. which profile has which song in their playlist).
