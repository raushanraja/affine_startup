# Affine dockercompose

## Configs
- Copy `nodemailer/.sample.env` to `nodemailer/.env`
    - Upadte the .env files
- Update data/affine/.env
- Update `data/mailrise/mailrise.conf`
- Add certficates in `data/mailrise/certs/`

## Run:
- `docker compose up -d`

## See logs
- `docker compose logs -f`
