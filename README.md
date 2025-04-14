<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parti API - People Endpoints</title>
</head>
<body>
    <h1>Parti API - People Endpoints</h1>
    <p>Here are the API endpoints for interacting with user and profile data on the Parti platform. The <code>{id}</code> placeholder can be replaced with a specific user ID.</p>
    <h2>Endpoints:</h2>
    <ul>
        <li><b>Get User Profile</b><br>
            <code>GET https://api-backend.parti.com/parti_v2/profile/user_profile/{id}</code>
        </li>
        <li><b>Get Global Moderators List</b><br>
            <code>GET https://api-backend.parti.com/parti_v2/profile/admin/global_mod/list</code>
        </li>
        <li><b>Get Livestream Channel Info</b><br>
            <code>GET https://api-backend.parti.com/parti_v2/profile/get_livestream_channel_info/{id}</code>
        </li>
        <li><b>Get Livestream Moderators</b><br>
            <code>GET https://api-backend.parti.com/parti_v2/profile/livestream/moderators/{id}</code>
        </li>
        <li><b>Get User Currency Info</b><br>
            <code>GET https://api-backend.parti.com/parti_v2/profile/user_currency_info/{id}</code>
        </li>
        <li><b>Get Pinned Message</b><br>
            <code>GET https://api-backend.parti.com/parti_v2/profile/pinned_message/{id}</code>
        </li>
        <li><b>Get Public User Chat Profile</b><br>
            <code>GET https://api-backend.parti.com/parti_v2/profile/user_profile_chat/{id}/public</code>
        </li>
    </ul>
    <p>Simply replace <code>{id}</code> with the specific user ID to access the corresponding profile data.</p>
</body>
</html>
