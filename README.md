# Portainer

## Configure OIDC SSO with Keycloak

1. Create an OIDC client in Keycloak.
2. Refer to the KeyCloak OpenID configuration page for values: `https://KEYCLOAK_FQDN/realms/REALM/.well-known/openid-configuration`.
3. The User identifer value must be `email` or it fails with an unauthorised error.
4. Scopes are `openid profile email`. Do not use commas as per the value placeholder text.
