# Day-28-Revision-Day-Everything-from-Day-1-to-Day-27
# 1. Linux Basics:
Linux is a free and open-source operating system.
Common commands:
pwd → show current directory ,
ls → list files,
cd → change directory ,
mkdir → create folder,
rm → delete file ,
# 2. Shell Scripting:
Shell script = file where we write Linux commands.
File extension: .sh
Run script:
chmod +x script.sh
./script.sh
# 3. Git Basics:
Git is used to track and manage code.
Important Commands:
git init → create repository,
git add . → add files,
git commit -m "message" → save changes,
git status → check changes,
git log → see commits,
# 4. GitHub:
GitHub is a cloud platform to store code.
Push code to GitHub:
git push origin main,
Pull latest code:
git pull origin main,
# 5. Git Advanced:
git branch → create branch,
git checkout branch-name → switch branch,
git merge branch-name → merge branch,
git rebase → reapply commits,
git stash → save temporary changes,
git reset --soft HEAD~1 → undo last commit (keep changes),
git revert → undo commit safely,
# 6. GitHub CLI:
GitHub CLI lets you manage GitHub from terminal.
gh auth login → login,
gh repo create → create repo,
gh issue create → create issue,
# 7. Docker Basics:
Docker is used to create containers.
Important Commands:
docker ps → show running containers,
docker ps -a → show all containers,
docker run → create container,
docker stop → stop container ,
docker start → start container,
docker exec -it container_name,
bash → run command inside container,
docker attach → attach to running container,
docker system prune → clean unused data,
#8. Dockerfile:
To create Docker image:
FROM ubuntu
RUN apt update
CMD ["echo", "Hello"]
Build image:docker build -t myimage .
