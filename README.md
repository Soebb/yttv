# YTTV
Python API for YouTubeTV (https://youtube.com/tv)

## Installation
```bash
poetry install
wget https://github.com/gorhill/uBlock/releases/download/1.42.4/uBlock0_1.42.4.firefox.signed.xpi
poetry run python yttv.py
```

## Testing
```bash
poetry run pytest
```

## docker
### docker-compose
```bash
docker-compose up -d
```

## Todo
### 0.1.X
- [X] Get YouTube TV Page
- [X] Go to Settings
- [X] Get TV Code
- [X] Add script block
- [X] Get multiple TV Code
- [X] Persistence
- [ ] Dockerize
- [ ] Add automated XPI Download
- [ ] Add Tests
- [ ] Add Docs
- [ ] Add Versioning
- [ ] Make python package
### 0.2.X
- [ ] Enhance crawling template creation (Maybe use accesible_name) 
- [ ] Enhance speed (check if site is fully rendered)
- [ ] Enhance dockerfile (check if site is fully rendered)
### 0.3.X
- [ ] Think about new options and add them
