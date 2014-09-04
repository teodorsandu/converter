function metric_standard(inputM){
		if(inputM == "IN"){
			FT = document.getElementById("inches").value * 0.0833333;		//metric to standard calcs function
			YD = document.getElementById("inches").value * 0.0277778;
			MI = document.getElementById("inches").value * 1.5783e-5;
			CT = document.getElementById("inches").value * 2.54;
			MT = document.getElementById("inches").value * 0.0254;
			KM = document.getElementById("inches").value * 2.54e-5;
			document.getElementById("kilos").value = KM.toFixed(2);
			document.getElementById("meter").value = MT.toFixed(2);
			document.getElementById("cent").value = CT;
			document.getElementById("miles").value = MI.toFixed(2);
			document.getElementById("yards").value = YD.toFixed(2);
			document.getElementById("feet").value = FT.toFixed(2);
		}else if (inputM == "FT") {
			IN = document.getElementById("feet").value * 12;
			YD = document.getElementById("feet").value * 0.33333;
			MT = document.getElementById("feet").value * 0.3048;
			MI = document.getElementById("feet").value * 0.000189394;
			CT = document.getElementById("feet").value * 30.48;
			KM = document.getElementById("feet").value * 0.0003048;
			document.getElementById("kilos").value = KM.toFixed(2);
			document.getElementById("cent").value = CT.toFixed(2);
			document.getElementById("miles").value = MI.toFixed(2);
			document.getElementById("meter").value = MT.toFixed(2);
			document.getElementById("yards").value = YD.toFixed(2);
			document.getElementById("inches").value = IN;
		}else if (inputM == "YD"){
			IN = document.getElementById("yards").value * 36;
			FT = document.getElementById("yards").value * 3;
			MI = document.getElementById("yards").value * 0.000568182;
			CT = document.getElementById("yards").value * 91.44;
			MT = document.getElementById("yards").value * 0.9144;
			KM = document.getElementById("yards").value * 0.0009144;
			document.getElementById("kilos").value = KM.toFixed(2);
			document.getElementById("meter").value = MT.toFixed(2);
			document.getElementById("cent").value = CT.toFixed(2);
			document.getElementById("miles").value = MI.toFixed(2);
			document.getElementById("feet").value = FT;
			document.getElementById("inches").value = IN; 
		}else if (inputM == "MI"){
			IN = document.getElementById("miles").value * 63360;
			FT = document.getElementById("miles").value * 5280;
			YD = document.getElementById("miles").value * 1760;
			MT = document.getElementById("miles").value * 1609.34;
			CT = document.getElementById("miles").value * 160934;
			KM = document.getElementById("miles").value * 1.60934;
			document.getElementById("kilos").value = KM.toFixed(2);
			document.getElementById("cent").value = CT.toFixed(2);
			document.getElementById("meter").value = MT.toFixed(2);
			document.getElementById("yards").value = YD.toFixed(2);
			document.getElementById("feet").value = FT;
			document.getElementById("inches").value = IN;
		}else if (inputM == "CT"){
			IN = document.getElementById("cent").value * 0.393701;
			FT = document.getElementById("cent").value * 0.0328084;
			YD = document.getElementById("cent").value * 0.0109361;
			MI = document.getElementById("cent").value * 6.2137e-6;
			MT = document.getElementById("cent").value * 0.01;
			KM = document.getElementById("cent").value * 1e-5
			document.getElementById("kilos").value = KM.toFixed(2);
			document.getElementById("meter").value = MT.toFixed(2);
			document.getElementById("miles").value = MI.toFixed(2);
			document.getElementById("yards").value = YD.toFixed(2);
			document.getElementById("feet").value = FT;
			document.getElementById("inches").value = IN;
		}else if (inputM == "MT"){
			
		}

		};

	function liquidCalc(inputL){  // Liquid calculation function using instant calcs
		
		if(inputL == 'OU'){
			CP = document.getElementById('oz').value * 0.125;
			PT = document.getElementById('oz').value * 0.0625;
			QT = document.getElementById('oz').value * 0.03125;
			GL = document.getElementById('oz').value * 0.0078125;
			ML = document.getElementById('oz').value * 29.5735;
			L = document.getElementById('oz').value * 0.0295735;
			document.getElementById('ltr').value = L.toFixed(2);
			document.getElementById('mltr').value = ML.toFixed(2);
			document.getElementById('gals').value = GL.toFixed(2);
			document.getElementById('qts').value = QT.toFixed(2);
			document.getElementById('pint').value = PT.toFixed(2);
			document.getElementById('cup').value = CP;
		}else if(inputL == 'CP'){
			OU = document.getElementById('cup').value * 8;
			PT = document.getElementById('cup').value * 0.5;
			QT = document.getElementById('cup').value * 0.25;
			GL = document.getElementById('cup').value * 0.0625;
			ML = document.getElementById('cup').value * 236.588;
			L =  document.getElementById('cup').value * 0.236588;
			document.getElementById('ltr').value = L.toFixed(2);
			document.getElementById('mltr').value = ML.toFixed(2);
			document.getElementById('gals').value = GL;
			document.getElementById('qts').value = QT;
			document.getElementById('pint').value = PT;
			document.getElementById('oz').value = OU;
		}else if(inputL == 'PT'){
			OU = document.getElementById('pint').value * 16;
			QT = document.getElementById('pint').value * 0.5;
			CP = document.getElementById('pint').value * 2;
			ML = document.getElementById('pint').value * 473.176;
			L = document.getElementById('pint').value * 0.473176;
			GL = document.getElementById('pint').value * 0.125;
			document.getElementById('gals').value = GL;
			document.getElementById('ltr').value = L.toFixed(2);
			document.getElementById('mltr').value = ML.toFixed(2);
			document.getElementById('cup').value = CP;
			document.getElementById('qts').value = QT;
			document.getElementById('oz').value = OU;
		}else if (inputL == 'GL'){
			OU = document.getElementById('gals').value * 128;
			QT = document.getElementById('gals').value * 4;
			CP = document.getElementById('gals').value * 16;
			PT = document.getElementById('gals').value * 8;
			ML = document.getElementById('gals').value * 3785.41;
			L = document.getElementById('gals').value * 3.78541;
			document.getElementById('pint').value = PT;
			document.getElementById('ltr').value = L.toFixed(2);
			document.getElementById('mltr').value = ML.toFixed(2);
			document.getElementById('cup').value = CP;
			document.getElementById('qts').value = QT;
			document.getElementById('oz').value = OU;
		}else if (inputL == 'ML'){
			OU = document.getElementById('mltr').value * 0.033814;
			QT = document.getElementById('mltr').value * 0.00105669;
			CP = document.getElementById('mltr').value * 0.00422675;
			PT = document.getElementById('mltr').value * 0.00211338;
			GL = document.getElementById('mltr').value * 0.000264172;
			L = document.getElementById('mltr').value * 0.001;
			document.getElementById('ltr').value = L.toFixed(2);
			document.getElementById('gals').value = GL.toFixed(2);
			document.getElementById('pint').value = PT.toFixed(2);
			document.getElementById('cup').value = CP.toFixed(2);
			document.getElementById('qts').value = QT.toFixed(2);
			document.getElementById('oz').value = OU.toFixed(2);
		}else if(inputL == 'L'){
			OU = document.getElementById('ltr').value * 33.814;
			QT = document.getElementById('ltr').value * 1.05669;
			CP = document.getElementById('ltr').value * 4.22675;
			PT = document.getElementById('ltr').value * 2.11338;
			GL = document.getElementById('ltr').value * 0.264172;
			ML = document.getElementById('ltr').value * 1000;
			document.getElementById('mltr').value = ML.toFixed(2);
			document.getElementById('gals').value = GL.toFixed(2);
			document.getElementById('pint').value = PT.toFixed(2);
			document.getElementById('cup').value = CP.toFixed(2);
			document.getElementById('qts').value = QT.toFixed(2);
			document.getElementById('oz').value = OU.toFixed(2);
		}else if(inputL == 'QT'){
			OU = document.getElementById('qts').value * 32;
			CP = document.getElementById('qts').value * 4;
			PT = document.getElementById('qts').value * 2;
			GL = document.getElementById('qts').value * 0.25;
			ML = document.getElementById('qts').value * 946.353;
			L = document.getElementById('qts').value * 0.946353;
			document.getElementById('oz').value = OU.toFixed(2);
			document.getElementById('cup').value = CP.toFixed(2);
			document.getElementById('pint').value = PT.toFixed(2);
			document.getElementById('gals').value = GL.toFixed(2);
			document.getElementById('mltr').value = ML.toFixed(2);
			document.getElementById('ltr').value = L.toFixed(2);
		}
			
	};
	
	function resetAll() {									// function to rest all fields
		document.getElementById("tLength").value = "";
		document.getElementById("tWidth").value = '';
		document.getElementById("tHeight").value = '';
		document.getElementById("sqResult").value = '';
		document.getElementById("lValue").value = '';
		document.getElementById("rValue").value = '';
		document.getElementById("cResult").value = '';
		document.getElementById("pipeD").value = '';
		document.getElementById("velocity").value = '';
		document.getElementById("resultCalc").value = '';
		document.getElementById("c").value = '';
		document.getElementById("f").value = '';
		document.getElementById("k").value = '';
		document.getElementById("lbs").value = '';
		document.getElementById("ozs").value = '';
		document.getElementById("mgs").value = '';
		document.getElementById("gms").value = '';
		document.getElementById("kgs").value = '';
		document.getElementById('oz').value = '';
		document.getElementById('gals').value = '';
		document.getElementById('qts').value = '';
		document.getElementById('pint').value = '';
		document.getElementById('cup').value = '';
		document.getElementById('mltr').value = '';
		document.getElementById('ltr').value = '';
		document.getElementById("miles").value = '';
		document.getElementById("yards").value = '';
		document.getElementById("feet").value = '';
		document.getElementById("inches").value = '';
		document.getElementById("cent").value = '';
		document.getElementById("meter").value = '';
		document.getElementById("kilos").value = '';
		
}
	
	function weightCalc(inputW){								//weight function using instant calcs
		if(inputW == "OZ"){
			LB = document.getElementById("ozs").value / 16;
			GM = document.getElementById("ozs").value / 0.035274;
			MG = document.getElementById("ozs").value * 28350;
			KG = document.getElementById("ozs").value * 0.028350
			document.getElementById("lbs").value = LB.toFixed(2);
			document.getElementById("gms").value = GM.toFixed(2);
			document.getElementById("mgs").value = Math.round(MG);
			document.getElementById("kgs").value = KG.toFixed(2);
		}else if (inputW == "LB"){
			OZ = document.getElementById("lbs").value * 16;
			GM = document.getElementById("lbs").value * 453.59;
			MG = document.getElementById("lbs").value * 453592.33;
			KG = document.getElementById("lbs").value * 0.45359;
			document.getElementById("ozs").value = OZ.toFixed(2);
			document.getElementById("gms").value = GM.toFixed(2);
			document.getElementById("mgs").value = MG;
			document.getElementById("kgs").value = KG.toFixed(2);
			
		}else if (inputW == "MG"){
			OZ = document.getElementById("mgs").value * 0.000035274;
			LB = document.getElementById("mgs").value * 0.0000022046;
			KG = document.getElementById("mgs").value * 0.000001;
			GM = document.getElementById("mgs").value * 0.001;
			document.getElementById("ozs").value = OZ;
			document.getElementById("lbs").value = LB;
			document.getElementById("kgs").value = KG;
			document.getElementById("gms").value = GM;
			
		}else if (inputW == "GM"){
			OZ = document.getElementById("gms").value *  0.035274;
			LB = document.getElementById("gms").value * 0.0022046;
			MG = document.getElementById("gms").value * 1000;
			KG = document.getElementById("gms").value * 0.001;
			document.getElementById("ozs").value = OZ;
			document.getElementById("lbs").value = LB;
			document.getElementById("mgs").value = MG;
			document.getElementById("kgs").value = KG;
		}else{
			OZ = document.getElementById("kgs").value * 35.274;
			LB = document.getElementById("kgs").value * 2.2046;
			MG = document.getElementById("kgs").value * 1000000;
			GM = document.getElementById("kgs").value * 1000;
			document.getElementById("ozs").value = OZ;
			document.getElementById("lbs").value = LB;
			document.getElementById("mgs").value = MG;
			document.getElementById("gms").value = GM;
		}
		
		
}

	function sqTank() {
		var result = 0;
		var length = document.getElementById("tLength").value;
		var width = document.getElementById("tWidth").value;
		var height = document.getElementById("tHeight").value;
		result = length * width * height / 231;
		document.getElementById("sqResult").value = result.toFixed(2) + " Gallons";
}

	function rTank() {
		var result = 0;
		var length = document.getElementById("lValue").value;
		var radius = document.getElementById("rValue").value;
		result = (radius * radius * length * 3.14) / 231 ;
		document.getElementById("cResult").value = result.toFixed(2) + " Gallons";
	
	
}
	function calculateTemp(input) {
		if (input == "C") {
			F = document.getElementById("c").value * 9 /5 + 32;
			K = Number(document.getElementById("c").value) +  273.15;
			document.getElementById("f").value = Math.round(F);
			document.getElementById("k").value = Math.round(K);
        }else if (input == "F") {
		    C = (document.getElementById("f").value - 32) * 5 / 9;
		    K = (document.getElementById("f").value - 32) * 5 / 9 + 273.15;
		    document.getElementById("c").value = Math.round(C);
		    document.getElementById("k").value = Math.round(K);
        }else{
			C = document.getElementById("k").value - 273.15;
			F = document.getElementById("k").value * 9/5 - 459.67;
			document.getElementById("f").value = Math.round(F);
			document.getElementById("c").value = Math.round(C);
		
		}
	
	
	
	}
	
	function calculateCFM() {
		var result = 0;
		var pipe =  document.getElementById("pipeD").value;
		var veloA =  document.getElementById("velocity").value;
		var radiusIn = (pipe/12) / 2;
		
		result = radiusIn * radiusIn * 3.14 * veloA;
		
		document.getElementById("resultCalc").value = result.toFixed(2)+ " CFM";
}

	

	
