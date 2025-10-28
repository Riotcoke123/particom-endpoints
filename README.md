<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <img src="https://github.com/user-attachments/assets/8aefdbc2-8e48-43e9-a549-6df85a4424ac" alt="PARTI.COM" width="250" height="250">
    <h1>Parti API - Endpoints</h1>
    <p>Here are the API endpoints for interacting with user and profile data on the Parti platform. The <code>{id}</code> placeholder can be replaced with a specific user ID.</p>
    <h2>Endpoints:</h2>
    <ul>
        <li><b>Get User Profile</b><br>
            <code>GET https://api-backend.parti.com/parti_v2/profile/user_profile/{id}</code>
        </li>
        <li><b>Get Livestream Channel Info</b><br>
            <code>GET https://api-backend.parti.com/parti_v2/profile/get_livestream_channel_info/{id}</code>
        </li>
        <li><b>Get Recent Broadcast (VOD)</b><br>
            <code>GET https://api-backend.parti.com/parti_v2/profile/get_livestream_channel_info/recent/{id}</code>
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
        <li><b>Get User Profile Feed</b><br>
            <code>GET https://api-backend.parti.com/parti_v2/profile/user_profile_feed/{id}?&limit=5</code>
        </li>
        <li><b>Get User Chatroom</b><br>
            <code>GET https://api-backend.parti.com/parti_v2/profile/user_profile_chat/{id}/public</code>
        </li>
        <li><b>Get Admin Global Moderator List</b><br>
            <code>GET https://api-backend.parti.com/parti_v2/profile/admin/global_mod/list</code>
        </li>
    </ul>
    <p>Simply replace <code>{id}</code> with the specific user ID to access the corresponding profile data.</p>
    <p>as og 10/28/2025. This api is dead. Go to <a href="https://github.com/Riotcoke123/PARTI.COMAPIV2">2.0</a>
</body>
</html>
