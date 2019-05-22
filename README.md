# Sweater Video 8. Lets Code Admin And Roles

Whitelabel Error Page
This application has no explicit mapping for /error, so you are seeing this as a fallback.

Thu Nov 22 14:35:29 MSK 2018
There was an unexpected error (type=Forbidden, status=403).


сначала закомментируй @PreAuthorize("hasAuthority('ADMIN')") в UserController, далее под любым юзером логинся, и в userList через edit дай хоть одному юзеру админские права. Далее, из под админа можно на UserList попасть, из простого юзера - нет (не забудь раскомментировать @PreAuthorize)
