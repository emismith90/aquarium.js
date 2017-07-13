##A lightweight event aggregator

Officially the event aggregator of AA.js

##Usage

var aquarium = new Aquarium('pacific', true);
aquarium.whenPet('shark', 'whale', function (food) {
    console.log(food);
});

aquarium.whenPet('shark', function (food) {
    console.log('s2:' + food);
})

aquarium.pet('shark', 'feeding sharks');
aquarium.pet('whale', 'feeding whales');

##aquarium.js was developed by [emismith90].

