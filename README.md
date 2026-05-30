# Coach Marcela SEFAZ-BA 🎯

Seu coach de IA para aprovação no concurso de Agente de Tributos da SEFAZ-BA.

## Features
- 💬 **Coach IA** — Chat com Claude/OpenAI
- 🎙️ **Voz** — Fale com seu coach (STT/TTS)
- ⏱️ **Pomodoro** — Timer de estudo com anel de progresso
- 📚 **Matérias** — Gestão de conteúdo por disciplina
- 📊 **Histórico** — Rastreie seu progresso
- ⚙️ **Config** — Personalize seu plano de estudo
- 📱 **PWA** — Instale como app no iPhone/iPad

## Stack
- **Frontend:** HTML5 + CSS3 (Flexbox, CSS Variables, clamp())
- **Backend:** Node.js + Render.com (OpenAI API)
- **Dados:** LocalStorage (offline-first)
- **Voz:** Web Speech API (português-BR)

## Como funciona

1. **Frontend** em Netlify
   - App responsivo e bonito
   - Funciona offline com localStorage
   - Manifesto PWA integrado

2. **Backend** em Render
   - Node.js HTTP server
   - Repassa requisições para OpenAI
   - Variáveis de ambiente: OPENAI_API_KEY, OPENAI_MODEL

3. **Deploy automático**
   - GitHub → Netlify (Frontend)
   - GitHub → Render (Backend)

## Instalação como PWA (iPhone/iPad)

1. Safari → `wonderful-cucurucho-b79f29.netlify.app`
2. Botão **Compartilhar** (⬆️)
3. **Adicionar à Tela Inicial**
4. Nome: "Coach SEFAZ"
5. **Adicionar**

## Como contribuir

```bash
git clone https://github.com/marcelasfreitas/coach-marcela-frontend.git
cd coach-marcela-frontend
# Fazer mudanças
git add .
git commit -m "Sua mensagem"
git push
```

Netlify faz deploy automático! 🚀

## Stack técnico

| Componente | Tecnologia |
|-----------|-----------|
| Frontend | HTML5, CSS3, Vanilla JS |
| Backend | Node.js, Express |
| API | OpenAI GPT-4o-mini |
| Banco | LocalStorage |
| Deploy | Netlify + Render |
| Voz | Web Speech API |
| PWA | Service Worker, Manifest |

## URLs

- **App:** https://wonderful-cucurucho-b79f29.netlify.app
- **Repo Frontend:** https://github.com/marcelasfreitas/coach-marcela-frontend
- **Repo Backend:** https://github.com/marcelasfreitas/coach-sefazba

## License

MIT — Desenvolvido com ❤️ para Marcela & Cora

---

**Dúvidas ou sugestões?** Abra uma issue no GitHub! 💬
