| **Роль**                     | **Группа пользователей**  | **Пример пользователя** | **Права** |
|------------------------------|---------------------------|-------------------------|-----------|
| **Разработчик (Namespace Reader)** | Разработчики | `dev-user` | `get`, `list`, `watch` (только в namespace `dev`) |
| **Специалист по ИБ (Secret Viewer)** | Специалист по ИБ | `sec-user` | `get`, `list`, `watch` для `Secrets` по всему кластеру |
| **DevOps (Cluster Reader)** | DevOps-инженеры | `devops-user` | `get`, `list`, `watch` для всех ресурсов кластера |
| **DevOps (Cluster Admin)** | DevOps-инженеры | `devops-admin` | Полный доступ `*` |
