---
title: Åshild Tellefsen Håland
role: Enhetsleder FoU, Ph.D og psykologspesialist i Kristiansand
avatar_filename: avatar.jpg
bio: Ph.D , psykologspesialist. Mottok prisen ”Årets doktorgrad i 2013” av Norsk
  Psykologiforening for forskning på atferdsterapeutisk gruppeterapi ved OCD
  (Obsessive-compulsive disorder).
interests:
  - Anxiety
  - OCD
superuser: false
user_groups:
  - Researchers
---

<ul>
  {{ $urlPre := "https://api.cristin.no" }}
  {{ $gistJ := getJSON $urlPre "/v2/persons/29860/results" }}
  {{ range first 5 $gistJ }}
    {{ if .category }}
      <li><a href="{{ .html_url }}" target="_blank">{{ .category }}</a></li>
    {{ end }}
  {{ end }}
</ul>
