Versions used:

Steps to run:

- npm install
- npm i --save-dev @types/node
- Convert the .js to .ts file
- npm start

Deploy:

- git add . && git commit -m "c" && git push origin main
  (or)
- git add . && git commit -m "c" && git push origin typescript
- git rm --cached file_name
  (
  .gitignore only ignores files that are not part of the repository yet. If you already git added some files, their changes will still be tracked. To remove those files from your repository (but not from your file system) use git rm --cached on them.
  )
- now login
- now
- vercel --prod ( to override later)

All in one command:

- npm install && npm run build && git add . && git commit -m "c" && git push origin main && now && vercel --prod

Demo:

Part 1:
https://user-images.githubusercontent.com/55496113/222214457-a972a3d1-d3c6-4b83-a250-72aa8fd573c9.mp4

Part 2:
https://user-images.githubusercontent.com/55496113/222214472-3781388e-6dc5-405d-8554-5a1c9fa74cfb.mp4
