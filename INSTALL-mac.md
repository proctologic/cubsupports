* Title: drphil.rb - Voting Bot - Mac Installation
* Tags: rubybear ruby bears bearshares curation
* Notes: 

<div class="pull-right">
  <img src="http://i.imgur.com/4iFmRDn.png" />
</div>

Before you can use `drphil`, you will need to install `bundler`.  If you are using the system version of `ruby`, you need to use `sudo` to install `bundler`:

```bash
$ sudo gem install bundler
```

On modern versions of macOS, attempting to use `git` will prompt its installation, which is a neat feature.  Just type `git` in the terminal and hit enter.  You'll get this dialog:

<img src="https://cl.ly/2F1K0L2U1l1w/download/Image%202017-04-21%20at%2010.06.43%20AM.png" />

Then you can proceed to do the normal installation steps.

```bash
$ git clone https://github.com/bearshares/cubsupports.git drphil
$ cd drphil
$ bundle install
```

Then run it:

```bash
$ ruby drphil.rb
```

To configure `drphil`, you will need to modify the `drphil.yml`.  You can edit it by typing `open -e drphil.yml` in the terminal.
