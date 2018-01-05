# Steps to Reproduce

1. Clone the repo with `git clone git@github.com:jerhinesmith/rails5_bug.git`
2. Switch to the project `cd rails5_bug`
3. Run `bundle install`
4. Execute the reproduction script with `./repro.rb`
5. The script should throw an `ActiveRecord::StatementInvalid` exception
