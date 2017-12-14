
# Lychee

## Usage:

### Build

```bash
docker build ./ --tag lychee
```

### Run
```bash
docker run
sudo docker run -d  -p "80:80" -p "9000:9000" -v /your-path/uploads/:/uploads/ -v /your-path/data/:/data/ --name my-lychee lychee
```
