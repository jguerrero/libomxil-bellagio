if WITH_FFMPEGCOMPONENTS
    MAYBE_FFMPEG = ffmpeg
    MAYBE_FILEREADER = filereader
    MAYBE_PARSER_3GP = parser3gp
endif

if WITH_AUDIOEFFECTS
    MAYBE_AUDIO_EFFECTS = audio_effects
endif

if WITH_MADCOMPONENTS
    MAYBE_MAD = mad
endif 

if WITH_ALSA
    MAYBE_ALSA = alsa
endif 

if WITH_VORBISCOMPONENTS
    MAYBE_VORBIS = vorbis
endif

if WITH_FBDEV_VIDEOSINK
    MAYBE_FBDEV = fbdev
endif

if WITH_VIDEOSRC
    MAYBE_VIDEOSRC = video_src
endif

if WITH_V4L2_VIDEOSOURCE
   MAYBE_CAMERA = camera
endif

if WITH_CLOCKSRC
    MAYBE_CLOCKSRC = clocksrc
endif

if WITH_JPEG
    MAYBE_JPEG = jpeg
endif

if WITH_XVIDEOSINK
    MAYBE_XVIDEO = xvideo
endif

SUBDIRS = $(MAYBE_FFMPEG) $(MAYBE_FILEREADER) $(MAYBE_AUDIO_EFFECTS) $(MAYBE_MAD) $(MAYBE_ALSA) $(MAYBE_VORBIS) $(MAYBE_FBDEV) $(MAYBE_VIDEOSRC) $(MAYBE_PARSER_3GP) $(MAYBE_CAMERA) $(MAYBE_CLOCKSRC) $(MAYBE_JPEG) $(MAYBE_XVIDEO)
