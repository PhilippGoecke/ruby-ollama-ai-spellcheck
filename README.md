# Ruby Ollama Ai Spellcheck

```bash
OLLAMA_HOST="http://0.0.0.0:11434" ollama serve
```
or
systemctl edit ollama.service
```editor
[Service]
Environment="OLLAMA_HOST="http://0.0.0.0:11434"
```
systemctl daemon-reload
systemctl restart ollama.service

irb -I . -r spellcheck.rb
