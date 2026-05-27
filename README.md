# RVC TECH - Website Redirect Repository

This repository hosts the public redirect website for the RVC TECH domain using GitHub Pages.

## Purpose

This repository is used to provide a lightweight public website and custom domain redirection service for professional branding and identity exposure.

The primary purpose is to redirect visitors from the corporate domain to the official LinkedIn profile.

## Files

* `index.html` → HTML redirect page
* `CNAME` → Custom domain mapping for GitHub Pages
* `README.md` → Repository documentation

## Domain

rvctech.com.br

## Public Endpoints

### Corporate Website

https://www.rvctech.com.br

### LinkedIn Profile

https://www.linkedin.com/in/ricardovirgenscoelho/

## Technologies

* GitHub Pages
* HTML5
* HTTPS
* Custom DNS
* GitHub CDN

## DNS Configuration

This repository uses GitHub Pages with custom domain configuration through Registro.br DNS.

### DNS Records

| Type | Name | Value |
|---|---|---|
| CNAME | www | ricardovirgenscoelho.github.io |

## Redirect Architecture

```text
www.rvctech.com.br
        ↓
GitHub Pages
        ↓
index.html
        ↓
LinkedIn Profile
