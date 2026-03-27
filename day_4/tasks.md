# Day 4 - Dockerfile and Image Building Basics

> Date: 13-03-2026


## Topics covered
1. Dockerfile core concepts
2. Build context and .dockerignore
3. Basic Dockerfile instructions:
   - FROM
   - RUN
   - COPY
   - CMD
   - WORKDIR
   - ENV
   - EXPOSE
4. Image tagging and versioning


## Tasks completed
- Wrote a basic Dockerfile (demo)
- Understood purpose of each main instruction
- Learned image tagging format (name:tag)


## Practice done
- Build image: docker build -t demo-app:v1 .
- Tag image: docker tag demo-app:v1 demo-app:latest
- Check image history: docker history demo-app:v1


## Next class plan
- Docker networking and storage (volumes vs bind mounts)
