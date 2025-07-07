# Changes 

## Overview

This document details the changes we made to the readability script for our use case

## Changes Made

- Byline is not guessed anymore (we don't try to pick it up from the article if we cannot find it)
- If we cannot find article text content, we return the rest of the metadata found (instead of returning null)
