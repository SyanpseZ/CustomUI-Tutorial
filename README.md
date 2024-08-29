follow the youtube video:

----------Required----------
using library: using SynapseZAPI;
initialize: public SynapseZAPI.SynapseZAPI synapseZAPI = new SynapseZAPI.SynapseZAPI();

Injection: synapseZAPI.Inject(Directory.GetCurrentDirectory());
Execution: synapseZAPI.Execute(Directory.GetCurrentDirectory(), fastColoredTextBox1.Text);

----------Optional----------
Clear button: fastColoredTextBox1.Text = "";
Open File/Save File: https://pastebin.com/NALEEPtD
