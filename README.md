# rat-man-tidbyt

First, replace `/Users/jbarclay` with `/Users/<your_username>` in `deployment/com.everythingisgray.rat-man.plist`. Next, replace `confidently-realistic-replete-alewife-bb3` with your own device ID and `RatManClock` with your own [installation ID](https://github.com/tidbyt/pixlet#push-as-an-installation). Finally, replace `event_time` and `event` with your own event time and event in `run_rat_man.sh`.

```sh
brew update && brew install tidbyt/tidbyt/pixlet
cp deployment/com.everythingisgray.rat-man.plist ~/Library/LaunchAgents/
launchctl load ~/Library/LaunchAgents/deployment/com.everythingisgray.rat-man.plist
```
