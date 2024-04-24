## Simulation slow subscriber
<img src ="img/ss1.png">
From the image above, we can see that there's a spike in delay graph up until 20 message. This happen because we add delay in the subscriber as long as 1 second. Even though the delay is only 1 second, because I sent many message in a short span of time, there's a spike in the delay.