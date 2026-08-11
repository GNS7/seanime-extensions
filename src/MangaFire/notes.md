- Suggestion: Add Volumes, needs a vrf builder
- Add option to use chapters or volumes
- Volumes need to be filtered client side, since the api doesn't accept parameters

/search doesn't exist anymore, use /browse or /api/titles

Example: /api/titles?

keyword=soul+eate
content_rating%5B%5D=safe
content_rating%5B%5D=suggestive
order%5Brelevance%5D=desc
page=1
limit=30
vrf=8sK3xtqdFZdOu6WNqS1bZ0shnUDqyRXMnh4NlZ7aYCPUhmAbm1C1qPzeL_OIIf0obIggCZIHJHIF_VdagQOsZhrpZQ20eDbJKAVWSvFWStI2yMb-v7F3P4X0mh8ulXqHl8py9AJwsZlaOicqWwadHvzkyw

- Ajax doesn't seem to work now, use /api/titles/${mangaId} /chapters | /volumes

- To get pages from chapter/volume use /api/* /${chapterId} | /${volumeId}

- Possible parameters chapter
api/titles/2z2/chapters?

language=en
sort=number
order=desc
page=1
limit=20
vrf=8sK3xtqdFdvBwaXHPgfZoAgUbCu9Ys0QMRDJo30NNjW76zYX3zwsgg7XQhcMUprjCloTv5RFJGAaO7gid8wN6DI-VEpOETY

- Possible parameters volume

api/titles/2z2/volumes?

vrf=8sK3xtqdFdvBwaXHzFprcYvtjA