---
permalink: /services
layout: default
title: "Services"
description: "Real world Micro services"
---

## Overview

Micro services provide the fundamental building blocks for products, apps and services. They can be used in isolation 
or combined to create powerful distributed systems. The services are intended to be consumed by each other using RPC 
and from the external world through the Micro API. All services are built as open source software.

## Catalog

Services available thus far:

- address - Address lookup by postcode
- avatar - Generate an avatar
- bitcoin - Bitcoin price and transaction info
- cache - Fast access key-value storage
- carbon - Purchase carbon offsets
- chat - Instant messaging service
- comments - Add comments to any App
- contact - Store your contacts
- cron - Schedule cron jobs
- crypto - Cryptocurrency prices, quotes, and news
- currency - Exchange rates and currency conversion
- db - Serverless postgres database
- dns - DNS over HTTPS (DoH)
- email - Send emails in a flash
- ethereum - Ethereum API explorer
- evchargers - Find electric vehicle (EV) chargers wherever you go 
- event - Event stream processing
- file - Store, list, and retrieve text files
- forex - Foreign exchange (FX) rates
- geocoding - Address geocoding and reverse lookup
- google - Google search service
- holidays - Find the holidays observed in a particular country
- id - Generate unique IDs (uuid, snowflake, etc)
- image - Upload, resize, and convert images
- ip - IP to geolocation lookup
- lists - Make a list
- location - Real time GPS location tracking and search
- mq - PubSub messaging
- news - Get the latest news
- nft - Explore NFT Assets
- notes - Store and retrieve notes
- otp - One time password generation
- password - Generate strong passwords
- place - Search for places
- postcode - Fast UK postcode lookup
- prayer - Islamic prayer times
- price - Global commodities index
- qr - QR code generator
- quran - The Holy Quran
- routing - Etas, routes and turn by turn directions
- rss - RSS feed crawler and reader
- search - Indexing and full text search
- sentiment - Real time sentiment analysis
- sms - Send SMS messages
- space - Infinite cloud storage
- spam - Check if an email is spam
- stock - Live stock quotes and prices
- stream - Ephemeral message streams
- sunnah - Traditions and practices of the Islamic prophet, Muhammad (pbuh)
- thumbnail - Create website thumbnails
- time - Time, date, and timezone info
- translate - Language translation service
- user - Authenticate and manage users
- wallet - Virtual Wallet 
- weather - Real time weather forecast
- youtube - Search for YouTube videos

## Source

Find the source at [https://github.com/micro/services](https://github.com/micro/services)

## Usage

Run a service from source

```
micro run github.com/micro/services/helloworld
```

To call a service from another

```
import "github.com/micro/services/helloworld/proto"
```

Call it from the api

```
curl http://localhost:8080/helloworld
```

## Contribute

We welcome contributions of additional services:

- Services must be built using the Micro platform
- Any dependency must be configured using the Micro Config
- All services must include a README.md and be well commented

