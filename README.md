# docker-cheatsheet

# Docker status commands
```sh

docker ps 
docker stop ga_v5.3
docker rm ga_v5.3
docker-compose -f docker-compose.yml up -d
docker-compose down 

```d




# Running images from registries like (docker hub, biocontainer)
```sh
# Example 
docker run --rm -v $(pwd):/home/data -w /home/data alhumaidyaroob/weesam:latest   python3  weeSAM/weeSAM --help




```