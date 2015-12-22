---
layout: post
date: 2015-12-23 12:00:00 +0000
title: "Roman numeral"
---

{% highlight ruby %}

ROMAN_CONCOLLECTOR = [
	[1000, "M"],
	[900, "CM"],
	[500, "D"],
	[400, "CD"],
	[100, "C"],
	[90, "XC"],
	[50, "L"],
	[40, "XL"],
	[10, "X"],
	[9, "IX"],
	[5, "V"],
	[4, "IV"],
	[1, "I"],
]
def roman_convert(number)
	result = ""
		ROMAN_CONCOLLECTOR.each do |arabic, roman|
			while number >= arabic
			result << roman
			number -= arabic
			end
		end
	result
	end

	describe 'convert to roman' do
	[
		[3999, "MMMCMXCIX"],
		[27, "XXVII"],
		[20, "XX"],
		[10, "X"],
		[9, "IX"],
		[6, "VI"],
		[5, "V"],
		[4, "IV"],
		[2, "II"],
		[1, "I"],
	].each do |arabic, roman|
		it "converts #{arabic} to #{roman}" do
			expect(roman_convert(arabic)).to eq(roman)
		end
	end
end

{% endhighlight %}

