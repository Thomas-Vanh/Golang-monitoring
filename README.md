# Golang Monitoring

## The Mission

The market is full to the brim with a plethora of amazing monitoring tools, some of which go as far as offering a full blown graphical dashboard collecting metrics on your entire system in a single unified interface, isn't it great?! Well, this challenge will have you throw all those carefully crafted pre-made solution out the window to **create your own** monitoring script using Golang!

You will have multiple days to make it as **useful** (_collect memory usage, disk usage, top running processes, ..._) and **fancy** (_interactive interface_, _features_, _..._) as possible. The goal is for you to **be creative** and **make it your own**! As such, we won't give you clear instructions to follow nor specific features to implement. Still, we are no monster so here are some idea to inspire you:

- Make an interactive [curses interface](https://en.wikipedia.org/wiki/Curses_(programming_library)) (_or similar_) for your script.
- Deploy your script on a machine you manage and use something like [cron](https://en.wikipedia.org/wiki/Cron) to execute it once an hour.
- Collect metrics every hour and store them in an [CSV file](https://en.wikipedia.org/wiki/Comma-separated_values).
- If the state of the machine is critical (_not enough ram_, _..._), notify yourself by mail.
- If there is an error in the system's log, notify yourself by mail.
- Send yourself a system report once a week.

This challenge is also a great opportunity for you to research **what is worth monitoring** on a Linux System. You should take the to surf the web on the matter.

## Complementary Resources

* ARTICLE: [CronJob: A Comprehensive Guide](https://www.hostinger.com/tutorials/cron-job)
* LIBRARY: [Promptui](https://github.com/manifoldco/promptui)

## Expected Output

At the end of this challenge you should be **able to use Golang to write simple projects**, which should be **verifiable by the source code** you wrote to solve the exercise.