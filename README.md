# Hello, MediaConvert!

This is the code project for the [Hello, Cognito!](https://davidpallmann.hashnode.dev/hello-mediaconvert) blog post. 

This episode: AWS Elemental MediaConvert and video transcoding. In this Hello, Cloud blog series, we're covering the basics of AWS cloud services for newcomers who are .NET developers. If you love C# but are new to AWS, or to this particular service, this should give you a jumpstart.

In this post we'll introduce MediaConvert and use it in a "Hello, Cloud" .NET program to transcode video. We'll do this step-by-step, making no assumptions other than familiarity with C# and Visual Studio. We're using Visual Studio 2022 and .NET 6.

## Our Hello, MediaConvert Project

We'll first create input and output S3 buckets, then write a .NET program that launches a MediaConvert job. The job will transcode a source video to MP4 and MOV formats. 

See the blog post for the tutorial to create this project and run it on AWS.

