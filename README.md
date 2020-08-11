# Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

> Do not overuse it, or your account might be banned by Heroku.

## FAQ

### It automatically stop after 30 minutes, and files were lost.

It is because Heroku's free dyno will idle when there is no incoming request within 30 minutes, and your files will be deleted too, this is why you might want to use Rclone.

### Can I delete files?

No. Just wait for its idling, and your files will be deleted.

### You said it will idle automatically, so I can't download large files?

It will generate fake requests when there are downloading or uploading tasks, so it won't idle when your files aren't completed.

### I don't know how to setup Rclone, can you help me?

No. I thought the instructions above are enough.
