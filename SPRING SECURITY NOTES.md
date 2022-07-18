#SPRING SECURITY NOTES

1. Create config class
    - @Configuration
    - @EnableWebSecurity
    - extends WebSecurityConfigurerAdapter
    - @Override protected void configure(HttpSecurity http)
    - @Bean @Override public UserDetailsService userDetailsService()