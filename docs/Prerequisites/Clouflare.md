---
sidebar_position: 3
---

# Cloudflare Configuration

After you complete this process, you will have everything you need to set up the Cloudflare .env file.

## Create Account

Create a free account on [CloudFlare](https://www.cloudflare.com/).

## Add your domain

Select **Websites** on the sidebar and add your domain name.

## Update Nameservers

Cloudflare will provide two nameservers for you to take back to your domain registrar.

You will need to update the nameservers on your domain name with these values.

## Generate an API Token

In the top right corner, click the user icon and select **My Profile**

Then select **API Tokens** on the left sidebar.

Click **Create Token**

Click **Use Template** next to **Edit zone DNS**

**Permissions** should be set to `Zone` `DNS` `Edit`

Under **Zone Resources**, select either your specific zone, or all zones.

Click **Continue** and **Create Token**

You should now see your CloudFlare API token. Copy it and store it somewhere safe, you will need it later.
