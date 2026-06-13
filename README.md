# Panopto

Panopto is a video management platform for education and enterprise that provides a REST API for managing recordings, folders, sessions, users, and video analytics in corporate and academic settings.

## API Resources

- **REST API Documentation**: https://support.panopto.com/s/topic/0TO39000000EowMGAS/api
- **Interactive API Reference**: https://demo.hosted.panopto.com/Panopto/api/docs/index.html
- **GitHub Organization**: https://github.com/Panopto
- **Python API Examples**: https://github.com/Panopto/panopto-api-python-examples

## Authentication

The Panopto REST API uses OAuth2. Three authentication flows are supported:

1. Server-side Web Application
2. User-Based Server Application
3. Identity Provider Integration

## Rate Limits

- 5 requests per second per endpoint
- 100 requests per minute per endpoint
- 5,000 requests per hour per endpoint

Limits are tracked per OAuth2 client ID (authenticated) or client IP (unauthenticated) and apply independently to each API endpoint. HTTP 429 is returned when limits are exceeded.

## Maintainer

Kin Lane (kin@apievangelist.com)
