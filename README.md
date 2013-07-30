USING
======

Install hammer

```
gem install hammer --pre
```

Pull it down

```
git clone git@github.com:heroku/pigz-builder.git
cd pigz-builder
hammer build
```

you can also experment with it on a nice little dyno I made for you

```
heroku sudo run bash --app pigz-builder
mkdir ./output
mkdir ./build-dir
build ./build-dir ./output
```
