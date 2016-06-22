# How awesome is this page?

*not very?*

```ruby
class Door
    def initialize(state="closed")
        @state = state("open"||"closed")
    end
    def toggle
        if @state == "closed"
            @state = "open"
        elsif @state == "open"
            @state = "closed"
    end 
end

doors = Door.new(100)

100.times do
    doors.each do |door, num| 
        door.toggle 
        num += 1 
    end
end

puts doors.each_with_index
```

[Rosetta Code] (https://www.rosettacode.org/wiki/100_doors)
![Awesome Pic] (http://i.imgur.com/o2AeGAK.jpg)

