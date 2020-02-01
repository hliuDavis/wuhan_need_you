# Wuhan Need You

A website for publishing donation information to WuHan.

## Development

```
pip3 install -r requirements.txt
python3 run.py
```

## Deployment

The website is deployed by flask+uwsgi+nginx.

```bash
git clone https://github.com/gaohongwei/wuhan_need_you.git
cd wuhan_need_you
sudo deploy/install.sh
sudo systemctl status wuhan_need_you
```

If everything is OK, `http://127.0.0.1` is available, e.g. `wget http://127.0.0.1`.

For external access, make sure the server has port `80` open.
