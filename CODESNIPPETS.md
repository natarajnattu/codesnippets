# codesnippets

#merge two arrays in one while comparing keys
_.map(arrayone, function (item) {
        return _.extend(item, _.findWhere(arraytwo, {
            key: item.key
}));
