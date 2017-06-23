# Rails101 - User


## About Rails101

This is a series of projects to study / practice Rails. A project is usually some reuse module system, such as the user system, micropost system and etc.

### About Rails101 - User

This purpose of this project is teaching me how to build the user system with rails. It'll include the below features:

- Basically Sign-up & Sign-in User System
    + Use an email to sign up
    + login in
    + User profile settings
- Email active
- Forgot password
- Upload image / avatar
- Following & Followers
- Paging

## How Will I implement it?

I divided it into some stages, from simple to complex.

- Stage 1 - Development envirement configuration
    + rbenv(ruby: 2.4.1, rails: 5.1.1, .gems local gemsets)
    + Use the Rspec testframe
    + Use Bootstrap
- Stage 2 - A basically sign-up/sign-in user system
    + Use an eamil to sign up
    + Login in
- Stage 3 - Advanced sign-up/sign-in user system
    + Remember password
    + Email active
    + Forgot password
- Stage 4 - More user profile & user settings
    + user avatar uploading
    + some other user profile, such as Address
- Stage 5 - Following & Follower System
    + Can follow / unfollow someone
    + List the following users and followers
    + Paging
    + Friend recommendation

## Build

```bash
$ cd /path/to/project
$ gem install bundler
$ bundle install
$ rails server
```


## License

MIT