# Robot

Gem that allows you to move a robot around a 5x5 surface

## Installation

Add this line to your application's Gemfile:

    gem 'robot'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install robot

## Usage

Setup the robot

    $ position = Robot::Position.new(X, Y, ORIENTATION)
    $ robot = Robot::Robot.new(position)
    
Turn the robot 90 degrees left

    $ robot.left
    
Turn the robot 90 degrees right

    $ robot.right
    
Move the robot 1 space in the direction it's facing

    $ robot.move
    
Get the robot's X and Y axis and ORIENTATION

    $ robot.report
    
## Contributing

1. Fork it ( http://github.com/<my-github-username>/robot/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
