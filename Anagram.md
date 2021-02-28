var sort = function(str) {
return str.replace(/\s+/g, '').toLowerCase().split('').sort().join('');
}

var isAnagram = function(original, test) {
return original.trim() === test.trim() ? false : sort(original) === sort(test);
}
}  
}
