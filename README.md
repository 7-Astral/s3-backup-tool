# S3 Backup & Restore Tool

🗂️ Backup local folders to S3 with versioning  
🕑 Scheduled backups  
🌐 Streamlit dashboard  
🔐 Secure & versioned restores  

## Features

- Upload files with S3 versioning
- Restore by version
- Duplicate detection via SHA256
- Zip large folders for efficient backup
- Lifecycle policy to delete old versions
- Streamlit dashboard to manage backups
- Automated CI/CD pipeline
- Dockerized version

## Getting Started

1. Configure AWS credentials
2. Edit `backup_config.yaml`
3. Run `python backup.py`
4. Run `python restore.py`

## Advanced

- Run `streamlit run streamlit_app/app.py` for dashboard
- Build Docker container: `docker build -t s3-backup-tool .`
- Run in CI/CD (see `.github/workflows/ci.yml`)

## License

MIT
