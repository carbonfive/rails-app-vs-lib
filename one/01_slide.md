!SLIDE 
# <code>/app</code> vs. <code>/lib</code>

!SLIDE 
# What's in <code>/app</code> ?

!SLIDE
## What's in <code>/app</code> ?
# assets

!SLIDE 
## What's in <code>/app</code> ? #
# controllers

!SLIDE 
## What's in <code>/app</code> ? #
# helpers

!SLIDE 
## What's in <code>/app</code> ? #
# mailers

!SLIDE 
## What's in <code>/app</code> ? #
# models

!SLIDE 
## What's in <code>/app</code> ? #
# views

!SLIDE 
## What's in <code>/app</code> ? #
# validators

!SLIDE
# What's in <code>/lib</code> ?

!SLIDE 
## What's in <code>/lib</code> ? #
# assets

!SLIDE 
## What's in <code>/lib</code> ? #
# tasks

!SLIDE 
# What else do people
# dump in <code>/lib</code> ?

!SLIDE
## What else do people dump in <code>/lib</code> ?
# jobs
 
!SLIDE 
## What else do people dump in <code>/lib</code> ?
# services

!SLIDE 
## What else do people dump in <code>/lib</code> ?
# middleware

!SLIDE 
## What else do people dump in <code>/lib</code> ?
# analytics

!SLIDE bullets incremental
## What else do people dump in <code>/lib</code> ?
# basically:
* <code>!model</code>
* <code>!controller</code>
* <code>!view</code>

!SLIDE
# But why are we doing this?

!SLIDE
# Keep Application Logic
# Where it Belongs! #

!SLIDE
# In <code>/app</code>!!!

!SLIDE
# Rules of Thumb

!SLIDE
## Rules of Thumb
# All Bussiness logic 
# Belongs in <code>/app</code>

!SLIDE
## Rules of Thumb
# So <code>jobs</code>,
# <code>services</code>,
# <code>middleware</code>, etc
# should be in <code>/app</code>

!SLIDE
## Rules of Thumb
# Core extensions
# should be in <code>/lib</code>

!SLIDE 
## Rule of Thumb #
# Eventual Gems
# should be in <code>/lib</code>

!SLIDE 
# What about Tasks?

!SLIDE
# Convention has it expected
# under <code>/lib</code>

!SLIDE
## Rule of Thumb
# Follow Convention ...

!SLIDE
## Rule of Thumb
# ... but have the heavy
# lifting done in classes
# under <code>/app</code>

!SLIDE
# Previously you needed
# to configure the load
# path to bring directories
# in <code>/app</code>

!SLIDE
# You get it for free
# in Rails 3

!SLIDE
# BONUS DEBATE!

!SLIDE
# Is it pronounced
# "lib" or "l-eye-b"
