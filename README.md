# OOP-project-
class game
{
private:

gamestatemanager  gm;
bool isRunning=false;
public:

	
	void gamerun()
	{
		//microphone input 
		

		while (isRunning)
		{
		gm.update();
		gm.draw();

		}

}


};
