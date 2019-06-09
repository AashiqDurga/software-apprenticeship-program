# Credit Card Mask

Usually when you buy something, you're asked whether your credit card number, phone number or answer to your most secret question is still correct. However, since someone could look over your shoulder, you don't want that shown on your screen. Instead, we mask it.

Your task is to write a function maskify, which changes all but the last four characters into '#'.

#Examples
'4556364607935616' // should return "############5616"
'64607935616'      // should return "#######5616"
'1'                // should return "1"
''                 // should return ""

// "What was the name of your first pet?"
'Skippy'                                   // should return "##ippy"
'Nananananananananananananananana Batman!' // should return "####################################man!"