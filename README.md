Livebook contenant du matériel de support pour enseigner Elixir.

Ce matériel est écrit pour enseigner Elixir à des gens ayant déjà de l'expérience en programmation, pas à des débutants.

Utilisez la commande suivante pour l'éxécuter via Docker:

```bash
docker run -p 8080:8080 -p 8081:8081 -v $(pwd):/data -e LIVEBOOK_TOKEN_ENABLED=false --name elixir_crash_course ghcr.io/livebook-dev/livebook
```

Une fois le conteneur démarré, le livebook est disponible au lien suivant: http://localhost:8080.
