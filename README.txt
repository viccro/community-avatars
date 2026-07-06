NYT Communities avatar generator
======================

adding a frame
--------------
1. copy the image (png, 1024x1024px) to `public/frames`
2. run `make dev` to test the changes locally
3. open a pr
4. for releases, see below

commands
--------
make dev           run local dev server at port 8000
make build         generate the image manifest

releases
--------
- a tag prefixed with `v` will trigger a production release
- a merge to `main` will trigger a staging release

environments
------------
- production
  https://viccro.github.io/community-avatars

troubleshooting
---------------
- verify the sha-1 and the timestamp at https://viccro.github.io/community-avatars.txt
- verify that the correct images are included in https://viccro.github.io/community-avatars.txt


෴෴෴෴෴෴෴෴෴
෴෴෴෴෴
෴෴෴෴
෴

This project is built off of https://github.com/newsguildny/gavatar/, created by coolov!
