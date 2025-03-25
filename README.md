Define the CLK and DIN pins; set the CLK and DIN pins as shown in lines (50, 51, 185, 186)

static const int dinPin = 3;
static const int clkPin = 2;

PDM.setDIN(dinPin);
PDM.setCLK(clkPin);
