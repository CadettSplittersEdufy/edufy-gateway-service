# Edufy — API Gateway

Gateway for Edufy, a 10+ service microservices platform for streaming media (music, podcasts, video), built as a group project using Scrum (1-week sprints, Jira). The platform tags content by genre and artist, tracks playback history, and generates personalized recommendations based on a user's top genres, with a deliberate 20% slice reserved for genre exploration.

**My role: security and system integration.** I owned Keycloak authentication/authorization across the gateway and coordinated its integration with every downstream service — configuring the security layer, wiring routing (including StripPrefix rules for the recommendation and history services), managing the Docker Compose network so all services could reach each other, and adding endpoints as the gateway's needs evolved.

**Stack:** Spring Cloud Gateway, Keycloak (OAuth2/OIDC), Docker, Docker Compose.

**Related repos:** [edufy-user-service](link) · [edufy-ratings-service](link) — both built and owned by me, see their own READMEs.
