.NET FRAMEWORK 4.8

follow the youtube video:
https://www.youtube.com/watch?v=VzRaH6iqjtU

----------Required----------

initialize: public SynapseZAPI.SynapseZAPI synapseZAPI = new SynapseZAPI.SynapseZAPI();

Injection: synapseZAPI.Inject(Directory.GetCurrentDirectory());

Execution: synapseZAPI.Execute(Directory.GetCurrentDirectory(), fastColoredTextBox1.Text);

----------Optional----------

Clear button: fastColoredTextBox1.Text = "";

Open File/Save File: https://pastebin.com/NALEEPtD
