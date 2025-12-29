# Mahjong Hub

![Image](https://github.com/user-attachments/assets/c97d6aca-b246-4c7c-a65a-335651d0ca56)

## Repositories

### [mahjong-api](https://github.com/mahjong-hub/mahjong-api)
Django REST Framework backend providing mahjong tile detection through ML-based inference. Key features:
- **YOLOv11-based tile detection** from uploaded images
- **AWS integration** with S3 for secure image storage and SQS for async task processing
- **Celery workers** for background ML inference jobs
- **REST API** for mobile client integration
- **Tech stack**: Python, Django, Django REST Framework, PostgreSQL, Docker, AWS ECS/EC2

### [mahjong-mobile](https://github.com/mahjong-hub/mahjong-mobile)
Mobile application client for the mahjong platform. Key features:
- **Cross-platform support** for iOS and Android
- **Image capture and upload** for tile detection
- **Hand analysis interface** for viewing detected tiles
- **Tech stack**: TypeScript, React Native, Expo

## Project Overview

This organization develops tools to help mahjong players:
- **Tile Recognition**: Automatically detect and identify mahjong tiles from photos
- **Hand Analysis**: Analyze tile combinations and potential winning hands
- **Learning Support**: Assist new players in understanding tile patterns

## Contributing

Contributions are welcome. Please check individual repository README files for development setup and contribution guidelines.