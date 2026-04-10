git remote add upstream https://github.com/ReDI-School/fullstack_bootcamp.git || true
git remote set-url --push upstream no-push
git pull upstream main --rebase
git push origin main
echo "Fork setup complete. Work here, push to origin."
error: externes Repository upstream existiert bereits.
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Entpacke Objekte: 100% (4/4), 3.55 KiB | 3.55 MiB/s, fertig.
Von https://github.com/ReDI-School/fullstack_bootcamp
 * branch            main       -> FETCH_HEAD
   a787f08..dd256bf  main       -> upstream/main
Aktualisiere 2e1b5f1..dd256bf
Fast-forward
Everything up-to-date


**Fork setup complete. Work here, push to origin.**