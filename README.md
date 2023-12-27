# Audio Production Learning Checklist

## Audio fundamentals
- Decibels (this is kind of a ridiculous rabbit hole, so don't dive too deep, just try to get a basic understanding)
  - How the dB scale works in practice, specifically the logarithmic nature of it
  -  Difference between analog and digital dB (most relevant when mixing)
      -  Why are dB readings in recording environments negative numbers?
- Basic wave theory concepts
    - Amplitude
    -  Frequency
        -  What is it
        -  Hz
        -  Names of audio frequency ranges
            - Sub-bass
            - Bass
            - Low-mid
            - Mid
            - High-mid
            - Highs
                - Sibilance
                - Brilliance
        - Percieved directionality of high vs low frequencies
    - Phase (mostly important to understand for recording with mics as well as for mixing)
        - Phase cancellation - how it works, how to avoid it when recording and mixing
    - Positive feedback loops (aka just "feedback")
        - How to prevent
        - How to eliminate if happening
            - Change mic placement (especially if you've done something dumb like put a mic in front of a speaker)
            - Apply a notch filter
                -  Turn the gain up to "sweep" for the offending frequency and then eliminate it
- Channels
    - Stereo vs mono
        - When to record which?
    - Stereo field
      
-  How to read frequency response charts
    -  How to use them to select proper microphones for the desired source

-  Signal / noise ratio (SNR)
    - What is signal? What is noise?
    - Types of noise
    - How to identify and reduce noise (electrical or environmental)
    - Signal to noise ratio and target levels
    
- Gain
    - Gain Staging
        - TIP: The more you boost a signal, the more noise you tend to introduce. This applies to every step of the chain, so try to get a healthy input signal and maintain that as closely as possible without cutting/boosting the signal too much throughout the signal path
        
- Clipping
    - What is clipping?
    - Types - hard vs soft vs digital and how to identify each
        - When you might want it
        - How to prevent it if unwanted


## Acoustics  
- How to acoustically treat a room 
    - Ways to treat a room quickly and/or cheaply
    - Learn how surface materials affect sound reflections 
    - Types of treatment
        - Absorption panels
        - Diffusers (when and why)
        - Resonators (you probably won't deal with these)
- Echo and reverb
- Resonance (sympathetic frequencies)
    - This applies to mics as well, worth knowing about
        - Often this is what's being compensated for when trying to eliminate feedback with a notch filter
- Reverberation time (RT60)
- Flutter and other acoustic gremlins you might have to deal with
- How to take impulse responses from rooms

## Hardware fundamentals
### Microphones
- How mics fundamentally work
  - How they convert sound waves into electricity
  - How this signal is converted to digital signals
  - How it's re-converted to sound later
- General mic technique
    - Inverse-square law (google "inverse square law audio" because it's a more general physics concept too)
        - Look into how this affects frequency response too. Generally, the closer the source is to the mic, the more bass it picks up
    - Plosives and how to prevent them
        - Off-axis placement
        - Pop filters (air redirection ones like Stedman are best)
    - Mic bleed (or spill) and how to prevent it
    - Good mic placement for various instruments
        - Kind of just comes with experience unfortunately

- Research popular mics for various applications
    - Don't want to list a bunch here, but you could just ask me about some or look at what pros are using day to day
    
- Types of mic transducer
    - Large Diaphragm Condenser (LDC) - Requires phantom power
    - Small Diaphragm Condenser (SDC) - Requires phantom power
    - Dynamic - Doesn't require phantom power, but won't hurt the mic either
    - Ribbon - NEVER USE PHANTOM POWER, CAN DESTROY THE RIBBON

- Other mic form factors
    - Shotgun - usually used for audio for video and sometimes for drum overhead mics
    - PZM (or Boundary mic) - Often used for board rooms for conferences, but also sometimes used for hidden location mics
    - Lavalier mic - Placed on clothing 
    - Headset mics
    
- Microphone Polar Patterns - What are they, and when to use which
    - Main polar patterns
        - Cardioid
        - Super-Cardioid
        - Omnidirectional
        - Figure-8
        - Multi-pattern
    - Learn how different patterns pickup sound, depending on the angle
        - Learn how to use this to your advantage when recording
            - Off-axis rejection
        - Also learn how to mix and match polar patterns when recording in stereo
    - Stereo configurations
        - X/Y
        - A/B
        - Mid-Side (kind of pseudo-stereo were you can kind of dial in the amount manually, it's weird, but cool)
        - ORTF
        - Blumlein pair
        - There are a bunch of other configurations, but those will probably be your most common 
        
### Recording/Mixing Hardware
- Cabling (most common for audio)
    - XLR
    - TS/TRS
    - General cabling concepts
        - Shielding
        - "Balanced" vs "unbalanced" cabling
            - Cable length limitations for each
            - Signal loss 
            - Direct (DI) boxes to help circumvent some of these problems
- Preamps
- Equalizers
    - Major Types 
        - Parametric EQ
        - Graphic EQ
        - Low pass filter
        - High-pass filter
        - Band pass filter
        - Dynamic EQ
    - Concepts
        - Frequency
        - Q (Bandwidth)
        - Gain
        - Filter (curve) types - shelf, bell, cut, notch
        - Filter slope - how steep and what does this effect?
        - Boost
        - Attenuation
    - TIP: reducing frequencies is usually preferable to boosting them
- Compressors
    - How they work
        - Gain reduction
    - Threshold
    - Ratio
    - Attack/release
    - Makeup gain
    - Side chaining (not that important for what you'd probably be doing, don't worry about it)
- Converters (DAC and ADC)
    - Digital good time to look into digital audio concepts such as:
        - How is audio signal represented as digital bits? 
        - Sample rate
        - Bit depth
        - Bit rate
        - What impact do all 3 of these have on file sizes?
        - When to choose which?
            - Movies/video is typically 48kHz, music is typically 44.1kHz
            - Know what medium you're recording for, record at either that rate or exactly double that
                - If you don't record at an evenly divisible multiple (such as 96k for 48k), you can cause "artifacts" when downsampling
        - Nyquist-Shannon theorem (lol jk, unless you really want to)

## Location recording and other "good to knows"
- Lavalier (lapel) mics
    - How to actually make them sound decent and keep them hidden 
- Mic stands/placement
- Booms
    - Boom mic technique (important if you'll be assisting with location shoots)
        - Staying just out of frame
        - Wind filters / dead cats
- Headphone form factors
    - Which are best for recording and preventing bleed?

## Most important things to learn early on, for an assistant
- Basic terminology like gain, frequency, cable types, etc. Don't dive too deep into theory at first.
- How to be quiet (fr tho)
- How to properly wrap cable
- How to properly set up mic stands
- How to use gaffe tape properly, and where to put it
- How to help troubleshoot signal issues
- How to diagnose dead cables
    - How to build/repair cables
- How to not talk about right wing anarchism to paying customers
- How to safely seat mics in shock mounts
    - Fixing shock mounts with slipped bands
- How to avoid damaging equipment (for real tho)
- Mic placement for various instruments
    - Might be worth practicing/watching lots of videos on this if you're going to be helping record music 
    - You can always ask me for tips
