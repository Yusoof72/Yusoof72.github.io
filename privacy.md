---
title: Project Freedom privacy policy
---

# Project Freedom privacy policy

Last updated: 7 October 2026.

This policy applies to Project Freedom's owner-only Google/YouTube authorization and private-upload integration. It is not a public consumer service. The owner controls the Google account, intended YouTube channel, original video content and private GitHub repository used by the integration.

The unattended integration is currently being commissioned. The owner has verified local authorization; off-device credential enrollment and unattended upload qualification have not yet been completed. Off-device operation may begin only after the described security and commissioning gates pass.

## Information accessed and purpose

With the owner's authorization, the integration uses:

- The authorized channel identity, to confirm the exact intended upload destination.
- The owner's verified video, title, description, settings, thumbnail and authored captions, to perform the approved Private upload.
- Upload-session information, returned video/caption identifiers, privacy and processing observations, and applicable metadata/asset readbacks, to verify the upload and reconcile interruptions without blind duplicates.
- OAuth authorization material, solely to authenticate and refresh the owner's permitted Google API access.

The requested permissions are `youtube.upload` and `youtube.force-ssl`. The integration does not use its broader Google permissions to publish Public, delete videos, change ownership or channel settings, or modify unrelated videos. It does not request access to Gmail, Google Drive, contacts or unrelated Google account data.

Google user data is used only for the authorized upload, verification, recovery and owner notification. It is not sold, used for advertising, used to train general-purpose AI models or supplied to ChatGPT/Codex through prompts or outputs.

## Storage and security

The owner's existing local authorization is held in memory and, when saved, uses Windows user-bound DPAPI encryption on the owner's laptop. That local record is not exported into chat or Git.

When the off-device integration is qualified and explicitly enrolled by the owner, credentials and live resumable-upload session information are stored through GitHub's encrypted repository-secret service for the owner's private repository. The reviewed worker uses them in memory. Credential values must not be written to repository source, checkpoints, public pages, caches, ordinary artifacts or logs.

The private production repository and its data-only checkpoint references hold approved source content, package hashes, permitted resource identifiers and minimal operational verification/recovery records. Credential-free does not mean public: these records remain private. The original source package is controlled separately by the owner and is not downloaded from unrelated users' Google accounts.

## Providers and sharing

Google and YouTube process authorization, uploaded content and API requests under their policies. GitHub processes the owner's encrypted secrets, private repository/checkpoint data and qualified hosted-worker execution under its policies. Only data needed for these functions is provided to those services. The application does not sell Google user data or share it with advertisers or unrelated recipients.

The public documentation website contains only the app description and this policy. It has no application login, data-collection form, advertising or analytics script. The static hosting provider may process ordinary browser requests and connection information under its own privacy policy; this documentation does not claim that hosting produces no server logs.

## Retention, revocation and removal

Authorization material is needed only while the owner permits the integration to operate. Minimal operational identifiers and recovery records are retained as needed to verify uploads and prevent duplicates. Retention and removal of Google API data must comply with the [YouTube API Services Developer Policies](https://developers.google.com/youtube/terms/developer-policies); the integration must not retain data beyond its permitted purpose or policy limits.

The owner can revoke Google access through [Google Account permissions](https://myaccount.google.com/permissions). Revocation prevents continued authorized Google API use; it does not itself delete videos already held by YouTube or original production files controlled separately by the owner.

To remove application-held authorization, the owner can remove the corresponding encrypted GitHub repository secrets and local Windows authorization record using the owner-controlled storage interfaces. For removal of other application-held Google user data, contact the app owner's developer contact address displayed by Google for this OAuth application. Removal requests and revoked-access data must be handled within the applicable Google/YouTube policy deadlines. Automated removal has not been qualified, and this policy does not claim it has been implemented.

The uploader provides no video-deletion capability. The owner manages any desired deletion of channel content directly through YouTube.

## Google policy commitment and contact

Project Freedom's use and transfer of information received from Google APIs must adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements.

Support, privacy and data-removal requests go to the owner using the developer contact address displayed in Google's OAuth application information. The operator's existing public GitHub profile is [Yusoof72](https://github.com/Yusoof72). Do not include tokens, client secrets, cookies or private channel information in public messages.

[Return to the application homepage](./)

