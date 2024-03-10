const names = ["John", "Alice", "Bob", "Jane"];

names.forEach(name => {
    if (name.charAt(0).toLowerCase() === 'j') {
        console.log(`Goodbye ${name}`);
    } else {
        console.log(`Hello ${name}`);
    }
});

