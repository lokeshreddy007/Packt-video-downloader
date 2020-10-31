# Packt-video-downloader


## Requirements 

1. Account


## Usage

1. Login to Packt account
2. Open console, switch to network tab and try to play any video

```js
// https://subscription.packtpub.com/video/web_development/9781838648770/p1/video1_1/the-course-overview  
// https://subscription.packtpub.com/video/web_development/9781838648770/p1/video{number}_{number}/the-course-overview -- Example
// https://services.packtpub.com/products-v1/products/9781838648770/p1/video1_1  -- TO GET VIDEO URL 
```

3. Take above URL as an Example, then find the request with video{number}_{number} and find token 
4. Then to get the url of the Video send request with token ==> response will  DATA

```js
{
    "data": "https://d1ft11egbn8l.cloudfront.net/RESTful%20Web%20API%20Design%20with%20Node%20js%2012/Package/videos/video1_1.mp4?Expires=160412342342362804&Policy=9JoY3xFvJ9a9lxk77jruGNmYCNF4EfZgaZJNqKQh-6BLr5VSCSJm9mR95raO5Jz4W~jN0890E4JrYjPUQPB-ypx5CW7U9asdasdasJCDc4krHfcH~cIA0rUdQKtAw_&Key-Pair-Id=asfdasdasda",
    "captions": [
        {
            "type": "srt",
            "location": "https://d1ft11egbn8l.cloudfront.net/RESTful%20Web%20API%20Design%20with%20Node%20js%2012/Package/videos/srt/9781838648324234770-video1_1.srt?Expires=1604162804&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9kMWZ0MTFlZ2JuOGwuY2xvdWRmcm9udC5uZXQvUkVTVGZ1bCUyMFdlYiUyMEFQSSQxNjI4MDR9fX1dfQ__&Signature=QszM0FXiJfczF6m1X0SiZCYLSkHRpsMm8Ckc5DT8oyWQNlABqYjnvrrsbUi7qKtsjtEfZ2z4AFSAnlrtaWiC3SS7IetcROpMvZf~vAPEvp296EWVsf8EmBg4-zHU~ifUWgONI1Wx27YMly0FzXroHte0nWWP85FTclbavXGTr3Q_&Key-Pair-Id=asfasfasdaPJQL5PVZ47FA"
        }
    ]
}

```
5. Need to find way to automatically get url and download them
