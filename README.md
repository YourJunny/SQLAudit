# SQLAudit

I built this because I was tired of running an UPDATE and then praying. SQLAudit lets you change a
SQLite, Postgres or MySQL database and actually see what's going to happen first. Type what you want
in plain English (or write the SQL yourself, or just edit the grid), look at the rows it'll touch,
hit confirm. Messed up anyway? Undo it from History.

## Download

- [Windows](https://github.com/YourJunny/SQLAudit/releases/latest/download/SQLAudit-Windows-Setup.exe)
- [Mac](https://github.com/YourJunny/SQLAudit/releases/latest/download/SQLAudit-macOS.dmg) (works on both M1+ and Intel)
- [Linux](https://github.com/YourJunny/SQLAudit/releases/latest/download/SQLAudit-Linux.AppImage)

Grab the one for your computer and open it, that's it. You don't need to install anything else.
When I push an update the app will tell you and you just click "Restart to update".

First time using it? Go to the **Practice** tab. There's a fake store database in there you can mess
around with (you can't break it, and there's a reset button anyway) plus a checklist that shows you
where everything is.

### Heads up on the first launch

I haven't paid for code signing yet so your computer's going to be a bit suspicious the first time:

**Windows** - if it says "Windows protected your PC", click More info and then Run anyway.

**Mac** - open the .dmg and drag SQLAudit into Applications. When you open it, macOS will complain
it can't verify the app. Click Done, go to System Settings > Privacy & Security, scroll to the
bottom and click Open Anyway. Only have to do this once.

**Linux** - right-click the AppImage, Properties, and let it run as a program. Or `chmod +x` it.

## Found a bug?

Open an issue here and I'll take a look.

(The code itself is private, this repo is just for downloads.)
