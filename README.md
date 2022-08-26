# Segment.ioTrackingPixelAPISource
This is the unofficial Segment.io Tracking Pixel API that posts data to Segment's Tracking Pixel API source using the GTM Server-sides GA4 client.

# Author
Michael Ulrich

# Release Notes
| Date | Notes |
|-------|-------|
| 26 August 2022 | First version of the tag released. |

# Description
Once you have configured your GA4 page_view and event level data to post into GTM Server-side, this template automatically maps all events and user level data into the Segment.io Tracking Pixel API's required data schema. It then auto hashes the events and data parameters using base64 encryption and posts the required JSON object in the format that the API requires.

Example: Segment Debugger View of Tracking Pixel API Source Successfully Receiving Events
![Successful PII Email and Parameter Test](https://user-images.githubusercontent.com/53228114/186945751-2e3216fa-9f59-459e-a6b8-30cf9804bb20.png)
