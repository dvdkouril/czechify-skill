---
name: czfy
description: >-
  Converts text without accented characters into proper Czech words with
  diacritics, without changing any of the sentence structure and tone. Use when
  user asks to "czechify" or "czfy" a text, or when they ask to add
  diacritics.
---

# Czechify skill

Turn a source text into proper Czech words, with diacritics. Input is
typically text that is in Czech but written without accents.

## Instructions 

### Step 1: Parse text and add diacritics
The input text will very likely be written in Czech, but without accented
characters. You should rewrite such words with proper diacritics.

For example: "potrebovat" will be "potřebovat".

Do not translate English words. Do not fix grammar or change writing style.

### Step 2: Catch possible typos
Next, you should make sure that the sentence makes sense, even if it is not
100% grammatically correct. Suggest places where there might be a typo or the
wrong form of the word.

## Use cases
User mentions they want to czfy or czechify their text.

## Why
Many people who write in Czech on computers or mobile devices use an English
keyboard layout by default. In that case, using accented characters
(diacritics) takes a lot of time, and people have gotten used to both writing
and reading Czech text without such diacritics.
