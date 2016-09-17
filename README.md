# Quize1_887342
US_states = 
	{"Alabama" => "AL",
	"Alaska" => "AK",
	"Arizona" => "AZ",
	"Arkansas" => "AR",
	"California" => "CA",
	"Colorado" => "CO",
	"Connecticut" => "CT",
	"Delaware" => "DE",
	"District of Columbia" => "DC",
	"Florida" => "FL",
	"Georgia" => "GA",
	"Hawaii" => "HI",
	"Idaho" => "ID",
	"Illinois" => "IL",
	"Indiana" => "IN",
	"Iowa" => "IA",
	"Kansas" => "KS",
	"Kentucky" => "KY",
	"Louisiana" => "LA",
	"Maine" => "ME",
	"Maryland" => "MD",
	"Massachusetts" => "MA",
	"Michigan" => "MI",
	"Minnesota" => "MN",
	"Mississippi" => "MS",
	"Missouri" => "MO",
	"Montana" => "MT",
	"Nebraska" => "NE",
	"Nevada" => "NV",
	"New Hampshire" => "NH",
	"New Jersey" => "NJ",
	"New Mexico" => "NM",
	"New York" => "NY",
	"North Carolina" => "NC",
	"North Dakota" => "ND",
	"Ohio" => "OH",
	"Oklahoma" => "OK",
	"Oregon" => "OR",
	"Pennsylvania" => "PA",
	"Rhode Island" => "RI",
	"South Carolina" => "SC",
	"South Dakota" => "SD",
	"Tennessee" => "TN",
	"Texas" => "TX",
	"Utah" => "UT",
	"Vermont" => "VT",
	"Virginia" => "VA",
	"Washington" => "WA",
	"West Virginia" => "WV",
	"Wisconsin" => "WI",
	"Wyoming" => "WY"}
	
	
    US_states.each { |a,b| puts b if b[b.length-1]=='T' || b[b.length-1]=='N'}
    
    puts "====================="
    
    US_states_r = Hash[US_states.to_a.reverse]
    US_states_r.each{|a,b| puts"#{a}=>#{b}"}
    puts "====================="
    US_states.each{|a,b| puts a if (a[0]=="a" || a[0]=="e" || a[0]=="i" || a[0]=="o" || a[0]=="u" || a[0]=="A" || a[0]=="E" || a[0]=="I" || a[0]=="O" || a[0]=="U") && (a[a.length-1]=="a" || a[a.length-1]=="e" || a[a.length-1]=="i" || a[a.length-1]=="o" || a[a.length-1]=="u" || a[a.length-1]=="A" || a[a.length-1]=="E" || a[a.length-1]=="I" || a[a.length-1]=="O" || a[a.length-1]=="U")}
    
    
    
    ผมยังขาดความพยายามในการเรียนรู้ครับ
    
    
    
    
    
    
