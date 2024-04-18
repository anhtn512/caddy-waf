FROM anhtn512/caddy-waf:2.7

COPY ./Caddyfile /etc/caddy/Caddyfile

# Start the Caddy server
CMD ["caddy", "run", "--config", "/etc/caddy/Caddyfile", "--adapter", "caddyfile"]
