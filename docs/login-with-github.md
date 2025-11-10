---
title: Log in to Velu with GitHub
sidebar_position: 4
---

Learn how to authenticate with Velu using your GitHub account and get to the Update screen where you can collaborate with Velu AI on documentation updates.

## Prerequisites

- A GitHub account with access to the repositories that store your documentation content.
- Velu workspace access. If you have not been invited yet, reach out to your workspace administrator for an invitation.

## 1. Start the login flow

1. Navigate to the Velu sign-in page.
2. Select **Continue with GitHub**. Velu redirects you to GitHub to verify your identity.

> Velu currently supports GitHub SSO for login. Additional identity providers will be announced in future releases.

## 2. Authorize repository access

1. Review the GitHub authorization prompt.
2. Confirm that the requested scopes include the repositories that contain your documentation content. Velu requires this access so it can read and update docs on your behalf.
3. Click **Authorize Velu**. GitHub redirects you back to Velu.

If you do not see the correct repositories listed, ask a GitHub owner to grant you access and restart the sign-in flow.

## 3. Add collaborators (optional)

1. On the **Add collaborators** screen, enter the email addresses of any teammates who should collaborate on documentation updates.
2. Select **Add** after each email address. Velu will send invitations to the collaborators you list.
3. Click **Continue** when you are ready to move on. Roles are not assigned at this stage; collaborators inherit the default workspace permissions.

You can skip this step and invite collaborators later from the workspace settings.

## 4. Open the Update screen

After you confirm collaborators, Velu loads the **Update** screen:

- Start a documentation update chat by selecting **Start update chat** or **New update**.
- Use the chat composer to describe the changes you need. Velu AI will draft updates based on your instructions and the repository content it has access to.
- When Velu AI suggests changes, review them directly in the chat, request refinements, or apply the updates to the connected repository.

To return to this screen in the future, open Velu and choose **Update docs** from the navigation. If your GitHub session expires, you will be prompted to repeat the sign-in steps above.