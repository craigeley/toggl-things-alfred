# Toggl Things with Alfred

Alfred workflow that uses script filtering to find tasks in real-time from Things' "Today" list and then sends them to Toggl. The API key is stored in the workflow. The workflow uses the "project" property in Things to correspond with Toggl's "projects." If a Things item has no project, then it looks for its "area"; if it has neither it makes one up called "Inbox" that you can sort out in Toggl later.

Some caveats: because Things has no API, the work of finding Things is done via Applescript—which means that it is pretty dang slow. That's the reason it is limited to your "Today" view. Even then, I wouldn't recommend keeping more than 30 or so items in there. And if you have something you want to do that isn't in Today, you have to move it to today first. What's nice though, is that the script looks through the Today list only when it is invoked, so it can find things right away.

To speed things up, you can start to enter search terms while the script is still running.

Please leave any questions or suggestions as issues or pull requests.
