---
title: Project Freedom — owner-only YouTube uploader
---

# Project Freedom — owner-only YouTube uploader

Project Freedom is a private tool operated by its owner to prepare and upload the owner's original civil and structural engineering lessons to the owner's intended YouTube channel.

The YouTube integration is being commissioned. Unattended uploading has not yet been demonstrated or activated. These pages describe its approved purpose and data-handling policy; they do not claim completed automation or a Google verification decision.

## What the integration does

After its required qualifications and secure owner enrollment pass, the integration will:

- Receive an immutable, verified video package from the owner's production system.
- Verify the authorized channel before uploading.
- Upload the approved video as **Private**, with its approved metadata, thumbnail and captions.
- Read back the channel, privacy, processing and applicable asset information.
- Keep the upload identifier and recovery evidence to avoid blind duplicate uploads, and notify the owner.

The uploader has no Public visibility mutation, video deletion or channel-settings operation. Public release remains a separate owner action. This is an owner-only tool, with no public sign-up, customer accounts, checkout, advertising or commercial service offered through this documentation website.

## Google authorization

The owner authorizes the integration through Google's Desktop OAuth flow. It requests the existing `youtube.upload` and `youtube.force-ssl` permissions for the approved upload and verification work. Those Google permissions are broader than a private-only permission; the application's request boundary limits the uploader to its approved Private workflow and exact intended channel.

Authorization is never collected through this website. This website has no login form or application runtime and does not accept passwords, OAuth client files, codes, tokens, cookies or uploaded videos.

## Privacy, support and platform terms

Read the [Project Freedom privacy policy](privacy.html) for access, use, storage, sharing, retention and revocation information.

Support and data-removal requests go to the app owner's developer contact address displayed by Google for this OAuth application. The operator's existing public GitHub profile is [Yusoof72](https://github.com/Yusoof72). Do not post credentials or private channel information in a public issue or comment.

The integration uses YouTube API Services. Its use is subject to the [YouTube Terms of Service](https://www.youtube.com/t/terms), [YouTube API Services Terms of Service](https://developers.google.com/youtube/terms/api-services-terms-of-service), and applicable Google policies. See also the [Google Privacy Policy](https://policies.google.com/privacy).

