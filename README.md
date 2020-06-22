# Starter for deploying [fast.ai](https://www.fast.ai) models on [Render](https://render.com)

This repo was taken from the fast.ai course and used to create a learning engine to determine if a picture was of freestyle frisbee or ultimate frisbee.
There were very minimal changes to the repo, but the learning engine is used to determine those small sports subsets.
This repo is used to deploy [fast.ai](https://github.com/fastai/fastai) models on Render.

The sample app was described here https://fastai-v3.onrender.com. Test it out with bear images!

You can test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```

The guide for production deployment to Render is at https://course.fast.ai/deployment_render.html.

Please use [Render's fast.ai forum thread](https://forums.fast.ai/t/deployment-platform-render/33953) for questions and support.
