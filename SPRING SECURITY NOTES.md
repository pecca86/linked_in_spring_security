#SPRING SECURITY NOTES

1. Create config class
    - @Configuration
    - @EnableWebSecurity
    - extends WebSecurityConfigurerAdapter
    - @Override protected void configure(HttpSecurity http)
    - @Bean @Override public UserDetailsService userDetailsService()

## LDAP (Lightweight Directly Access Protocol)
    - Directory Structure
    - Native in many OS's
    - Interoperability
    - Scalability
    - Runs on a LDAP server
    - Use cases:
        * Security and authentication
        * Asset management
        * Binding, update, delete
        * Onboarding systems (users dynamically added)
        * HR Management systems (email lists etc.)
    
## OAUTH2
    - Protocol for providing access to HTTP services
    - Third-party access
    - System-to-system communication
    Parts:
        * Resource owner - User
        * Client - application requesting access
        * Resource server - posts protected data
        * Authorization server
    Tokens:
        * Access Token - short lived token that identifies the user
        * Refresh Token - longer lived token that refreshes the access token
        * Scope - Rights associated with the token
    Grants:
        * Authorization code grant
        * Implicit grant (web apps, mobile apps)
        * Client credential (System-to-system)
        