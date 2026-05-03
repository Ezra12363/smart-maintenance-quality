# SmartMaintenance - SonarCloud Setup

## Étape 1 + SonarCloud ✅

✅ Code spaghetti pushed GitHub: https://github.com/Ezra12363/smart-maintenance-quality

✅ sonar-project.properties + GitHub Action créés.

⏳ sonar-scanner installé globalement.

**Next: Lancer scan local**
```
sonar-scanner
```

Puis view https://sonarcloud.io/dashboard?id=smart-maintenance-quality (login GitHub).

Expected: Complexity haute, coverage 0%, Quality Gate FAIL.

Push changes: `git add . && git commit -m "Add SonarCloud config" && git push`



