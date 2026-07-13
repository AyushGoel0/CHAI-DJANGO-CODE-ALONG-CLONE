# CHAI-DJANGO-CODE-ALONG-CLONE

Code-along repository for the **Chai aur Code Django playlist**.

Playlist reference:  
https://www.youtube.com/watch?v=j6szNSzw4BU&list=PLu71SKxNbfoDOf-6vAcKmazT92uLnWAgy&index=1&pp=iAQB

---

## Goal

This repo is intentionally kept minimal at start.  
Only `README.md` is added right now.

I will progressively build the Django project locally while following the playlist and push code step-by-step.

---

## Local Setup (Windows PowerShell)

```powershell
uv venv
.venv\Scripts\activate
uv pip install django
uv pip freeze > requirements.txt
django-admin startproject chaiaurDjango
cd chaiaurDjango
python manage.py runserver
```

---

## Notes

- Python virtual environment is managed with `uv`.
- Django is installed using `uv pip`.
- Dependency snapshot is saved in `requirements.txt`.
- Initial Django project name: `chaiaurDjango`.

---

## Progress Tracker

- [x] Repository created
- [x] README initialised
- [ ] Virtual environment setup
- [ ] Django installation
- [ ] Start first project
- [ ] Run development server
- [ ] Continue module-by-module from playlist

---

## Author

Maintained by **@AyushGoel0**
