# Improve-Final-Fantasy-VII-Remake

all tested

[TextureStreaming]  
r.Streaming.PoolSize=2000 ； Streaming Pool Size too large(for example, 2600) will crash. Cause PS4 total RAM is too small, RAM and VRAM share 8G (approximately 5G available for games) RAM    
r.Streaming.MaxTempMemoryAllowed=40  
MemoryMargin=10  

[TextureQuality@]  
r.Streaming.MipBias=0          
r.MaxAnisotropy=16 ; AF 16X   
r.Streaming.PoolSize=2000    
r.Streaming.MaxEffectiveScreenSize=0  

[AntiAliasingQuality@]  
r.PostProcessAAQuality=3 ; default value 4 TAA too blur, value 3 balance more than other

[PostProcessQuality@]  
r.MotionBlurQuality=0 ; disable Motion Blur
r.AmbientOcclusionMipLevelFactor=0.4 ; improve AO.  
r.AmbientOcclusionMaxQuality=100 ; improve AO     
r.AmbientOcclusionLevels=-1 ; improve AO    
r.AmbientOcclusionRadiusScale=1.0 ; improve AO      
r.DepthOfFieldQuality=2 ; DOF so far so good
r.SceneColorFringeQuality=0 ; remove blur  
r.Tonemapper.GrainQuantization=0 ; remove grain  
r.Tonemapper.Quality=0 ; remove

[EffectsQuality@]  
r.DetailMode=2 ; improve detail
r.MaterialQualityLevel=1 ; improve material
