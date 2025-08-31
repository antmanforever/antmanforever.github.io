# antmanforever.github.io
<a href="https://github.com/antmanforever/antmanforever.github.io/releases/download/untagged-394ef97fb605d15ddb8f/animetv632.apk">animetv632</a>
<a href="https://github.com/antmanforever/antmanforever.github.io/releases/download/untagged-394ef97fb605d15ddb8f/EeveeSpotify-9.0.74.ipa">EeveeSpotify-9.0.74</a>
<a href="https://github.com/antmanforever/antmanforever.github.io/releases/download/untagged-394ef97fb605d15ddb8f/YouTubePlus_5.2b3.20.31.6.ipa">YouTubePlus_5.2b3.20.31.6</a>
<a href="https://github.com/antmanforever/antmanforever.github.io/releases/download/untagged-394ef97fb605d15ddb8f/YTMusicUltimate.8.33.ipa">YTMusicUltimate.8.33</a>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dan's Workshop</title>
    <script>
        document.addEventListener("DOMContentLoaded", function () {
            const redirects = {
                "/altstore": { name: "AltStore", url: "altstore://source/?url=https://github.com/dvntm0/AltStore/raw/refs/heads/main/repo.json" },
                "/feather": { name: "Feather", url: "feather://source/https://github.com/dvntm0/AltStore/raw/refs/heads/main/feather.json" },
                "/trollapps": { name: "TrollApps", url: "trollapps://add?url=https://github.com/dvntm0/AltStore/raw/refs/heads/main/feather.json" },
                "/sidestore": { name: "SideStore", url: "sidestore://source?url=https://raw.githubusercontent.com/dvntm0/AltStore/refs/heads/main/sidestore.json" },
                "/esign": { name: "ESign", url: "esign://addsource?url=https://github.com/dvntm0/AltStore/raw/refs/heads/main/esign.json" },
                "/gbox": { name: "GBox", url: "gbox://AddSource/https://github.com/dvntm0/AltStore/raw/refs/heads/main/gbox.json" },
                "/appdb": { name: "AppDB", url: "https://appdb.to/repos/import?url=https://github.com/dvntm0/AltStore/raw/refs/heads/main/feather.json" },
                "/scarlet": { name: "Scarlet", url: "scarlet://repo=https://github.com/dvntm0/AltStore/raw/refs/heads/main/scarlet.json" },
                "/krava": { name: "KravaSigner", url: "kravasigner://addRepo=https://github.com/dvntm0/AltStore/raw/refs/heads/main/feather.json" },
            };

            const path = window.location.pathname;
            const source = redirects[path];

            if (source) {
                document.getElementById("title").innerText = `Redirecting to ${source.name}...`;
                window.location.href = source.url;
            } else {
                document.body.innerHTML = "<h1>Link not found</h1><p>Or app not installed</p>";
            }
        });
    </script>
</head>
<body>
    <h1 id="title">Redirecting...</h1>
</body>
</html>
