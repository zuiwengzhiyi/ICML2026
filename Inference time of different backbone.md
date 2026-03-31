

|method|Video decoding|Image preprocessing|Feature extraction|Algorithm time|Frame rate of end-to-end system|
|-|-|-|-|-|-|
|LAVAD|-|-|-|-|1.32 fps|
|PerceptionEncoder+Flashback|3.56 ms|1.389 ms|14.752 ms|0.410 ms|50.74 fps|
|Qwen3-VL-Embedding+Flashback|3.96ms|0.10 ms|86.955 ms|0.532ms|11.47 fps|
|PerceptionEncoder+PRISM|3.56 ms|1.389 ms|14.752 ms|**0.084 ms**|50.75 fps|
|Qwen3-VL-Embedding+PRISM|3.96ms|0.10 ms|86.955 ms|**0.082ms**|11.48 fps|

End-to-end inference latency and system frame rate (FPS) breakdown across different model backbones

