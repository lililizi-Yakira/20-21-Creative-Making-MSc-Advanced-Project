# Unity3dGame-Fireworks-YifanLi


<!-- Ideally, now include at least one image of the work, using the work's URL (i.e., don't copy non-public-domain media into this repository.) --> 

<img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/1.jpg?raw=true">

### Description

Fireworks is an immersive third-person exploration game. It encourages people to explore the meaning of life and death. The theme of the game is the Player need to help the ghost of a dead bunny to realize its wishes. Player can explore in the game scene. The main gameplay is to talk to NPCs, pick up materials, and light fireworks. Free roaming is the focus of this work. In this mode, the audience is completely immersed in it, roaming freely in Sci-Fi City from a third-person perspective, fully exploring every detail, and collecting items together with the ghost in the game to complete tasks.
   
This game project provides players with a scenic and challenging journey. The gameplay is simple, and the player can concentrate on the scene. There are hyperloop suspended in the air, space vehicles, bright glass bars, modern shopping malls, and so on. There are robots, bionics, animals, and plants living here. High-tech and beautiful natural environment co-exist, like a utopia. 

### About: 
  - Creator: Yifan Li 20007301
  - Gameplay Demo (7mins): [Youtube Link](https://youtu.be/7sou8W0E_us)
  - Unity Original Work Download: [Dropbox Link](https://www.dropbox.com/s/om16nv9ei79niyb/u3d-Fireworks.zip?dl=0) 1.46GB
  - App Download(Win or Mac): [Download Link](https://lililizi-yakira.itch.io/fireworks-yifan-li) 
<img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/2.jpg?raw=true">

## I. Preparation

### 1. Unity version: 
  - Unity 2019.4.18  [Download Unity 2019.4.18](https://unity3d.com/cn/get-unity/download/archive?version=2019)
  
### 2. Inspiration: 
  - Journey(Game, 2012)[wiki](https://en.wikipedia.org/wiki/Journey_(2012_video_game)) A single theme to represent the game's emotional arc throughout the story.
  - No Man’s Sky(Game, 2016) [wiki](https://en.wikipedia.org/wiki/No_Man%27s_Sky) Space setting and background, content design.
  - The Flower We Saw That Day(Anime, 2013) [wiki](https://en.wikipedia.org/wiki/Anohana:_The_Flower_We_Saw_That_Day) Ghosts and unfulfilled wishes.
  - Sky Ladder: The Art of Cai Guo-Qiang(Documentary, 2016) [wiki](https://en.wikipedia.org/wiki/Sky_Ladder:_The_Art_of_Cai_Guo-Qiang) You can use fireworks to make a wish to the gods in the sky.
  
<!-- 
<img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/3-2.jpg?raw=true"> 
-->

### 3. Scripts language: C#

### 4. Game Conception:
Based on the above, I designed the main line of the game: The Player helps his dead bunny’s ghost fulfill it wish. The game scene is based on a future sci-fi city. Players can explore in the scene while collecting materials, lighting fireworks, and finally completing tasks.

## II. Build the game world

### 1. Credit:  For making this a better example, I've used a few assets, as I'm no artist myself.
  - Characters: 
  [Stylized Astronaut](https://assetstore.unity.com/packages/3d/characters/humanoids/sci-fi/stylized-astronaut-114298) a simple third person controller! 
  [Yasmin](https://assetstore.unity.com/packages/3d/characters/humanoids/humans/yasmin-lowpoly-character-144420) LOWPOLY CHARACTER.
  [Stinger Robot](https://assetstore.unity.com/packages/3d/characters/robots/stinger-robot-cute-series-203861).
  [Delivery Robot](https://assetstore.unity.com/packages/3d/characters/robots/delivery-robot-cute-series-203517).
  [Hermit Robot](https://assetstore.unity.com/packages/3d/characters/robots/hermit-robot-cute-series-197946).
  [Grid Robot](https://assetstore.unity.com/packages/3d/characters/robots/grid-robot-cute-series-204645)These are some very smart robots！


  - Scenes:
  [AZURE Nature](https://assetstore.unity.com/packages/3d/environments/fantasy/azure-nature-167725#description) Use custom shaders to freely change colors and add moss, snow and other coatings on the model. Create four seasons scenes.
  [Metropia - Sci-Fi City](https://assetstore.unity.com/packages/3d/environments/metropia-sci-fi-city-140356) An environment asset pack inspired by the art of the "Studio Ghibli".


  - Objects: 
  [Space Polygons](https://assetstore.unity.com/packages/3d/vehicles/space/space-polygons-lander-pack-123794) Lander Pack.
  [Fireworks](https://assetstore.unity.com/packages/vfx/particles/fire-explosions/fireworks-collection-6037#reviews) Amazing quality asset！
  [Low Poly Rocks Pack](https://assetstore.unity.com/packages/3d/environments/low-poly-rocks-pack-70164) a huge variety of different rocks


  - Sounds:
  [Freesound](https://freesound.org/) Here I found the ambient music of the forest, the sound of fireworks exploding, and the sound of picking up objects.
  
  
  - Effects:
  [MK Glow](https://assetstore.unity.com/packages/vfx/shaders/fullscreen-camera-effects/mk-glow-90204) MK Glow simulates bright surface scattering of light. It is tweaked towards artists for an easy and intuitive workflow.
  [Butterflies pack 3D](https://assetstore.unity.com/packages/vfx/particles/butterflies-pack-3d-141259) Butterflies that fit perfectly into any game!
  
 

### 2. Design 2d map

After I decided on the theme of the game, I then designed the main content. First draw a sample map through Adobe illustrator.

<img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/4map.png?raw=true">

     

### 3. Build 3d world

According to the 2d map design, importing 3d Prototyping resources into Unity mainly uses prefabs that have been made in the Prefabs folder of various Assets resource packages.

* Terrain

Design the total terrain, including grass, snow and mines.
 <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/WX20211117-185426@2x.png?raw=true">
  
  Improve the terrain, use Terrain Tools to draw grass, trees, flowers, and a big red tree that shines on the ground. 
  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/WX20211117-201608@2x.png?raw=true">
  
  And use the Wind Zone tool to add the effect of shaking with the wind to all plants.
  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/WX20211117-201628@2x.png?raw=true">


* Sky and Buildings

Import prefabs of various buildings into the scene.
  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/WX20211117-202806@2x.png?raw=true">
  
Add a blue-purple gradient sky.
  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/WX20211117-201656@2x.png?raw=true">
  

* Characters

Import the third-person controller (Astronaut) and ghost models.
   <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/WX20211117-203328@2x.png?raw=true">
    
Import the models of all characters, and use the Avatar function in Unity to design actions for the characters.    
  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/WX20211117-201750@2x.png?raw=true">
    

* Pick up objects

Choose 7 items as the props to be picked up in the game, and use the MK Glow plug-in to add fluorescent effects to them.
  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/WX20211117-201800@2x.png?raw=true">

  
* Final scenes demo:
  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/WX20211117-203221@2x.png?raw=true">

## III. Interactive scripts

### 1. Ghost Follow Player

NavMesh is a kind of path finding system that comes with Unity, which can easily and simply realize the effect of AI automatic path finding.

NavMesh is a kind of pathfinding based on convex polygonal mesh. The whole pathfinding process is divided into at least two parts: Navigation mesh construction and pathfinding algorithm. The navigation grid is roughly equivalent to Bake in Unity, and it looks like this after baking the scene:
  
  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/bake.png?raw=true">
As you can see, it bake the terrain that can be walked into blue. Combined with the C# script, set the player's real-time coordinates as the destination, and the ghost can follow the player's activity trajectory to find its way automatically.  

  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/7follow.png?raw=true">
  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/NavMeshGoals.png?raw=true">

### 2. Dialogue

Trigger is used to trigger events:
When the game object bound with the collider enters the trigger area, the OnTriggerEnter() function on the trigger object will be run, and the IsTrigger checkbox needs to be checked in the collider component in the inspector.

Set NPCs to Trigger. When the Player approaches, it will trigger the display of the text under the Canvas list.
  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/8-2talk.png?raw=true">

The picture below is a demo of the dialogue between Player and npc11.
  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/8talk.png?raw=true">
  <img src="">

### 3. Pick Up

Similarly, for the function of picking up items, I also used Trigger to detect collisions.
  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/10pick.png?raw=true">


### 4. Count

When the Player picks up the item, I added a Count function, which is displayed in the upper left corner of the screen in the form of UI Text.
  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/11count.png?raw=true">

When the player picks up 7 items, the upper right corner of the screen will prompt the player:
'Now you can go to the Sea of Flowers to light the fireworks^_^'

### 5. Light Fireworks

if (count >= 7), it means that the player has collected all seven items. At this time, the player will follow the prompt to the center of the flower sea. A Trigger is hidden in the place where the butterfly is dancing. When the player touches this trigger, the effect and sound of the firework lighting can be triggered.

  <img src="https://github.com/lililizi-Yakira/MSc-Advanced-Project-YifanLi/blob/main/Materials/12fireworks.png?raw=true">
  At the same time, the last words Ghost said to Player will be displayed in the upper right corner of the game screen.
"My wish is to feel the beauty and warmth of this world, and now my wish has come true, thank you."

## IV. Final Code 

### Player.cs

    using UnityEngine;
    using System.Collections;
    using UnityEngine.UI;

public class Player : MonoBehaviour {

		private Animator anim;
		private CharacterController controller;

		public float speed = 600.0f;
		public float turnSpeed = 400.0f;
		private Vector3 moveDirection = Vector3.zero;
		public float gravity = 20.0f;

	    public Text countText;
	    public Text GuideTalk;
		public Text winText;
	    public Text npc0Text;
	    public Text npc0Text2;
	    public Text npc1Text;
	    public Text npc2Text;
	    public Text npc3Text;
   	    public Text npc4Text;
	    public Text npc5Text;
	    public Text npc6Text;
	    public Text npc7Text;
	    public Text npc8Text;
	    public Text npc9Text;
	    public Text npc10Text;
	    public Text npc11Text;
	    public Object guide;
     	public GameObject Fireworks;
	    public GameObject button;
	    public GameObject Ghost;
	    public GameObject Ghost2;
	    public GameObject butterfly;

	    public AudioSource _1;

	    private int count;

	void Start () {
			controller = GetComponent <CharacterController>();
			anim = gameObject.GetComponentInChildren<Animator>();
		    SetCountText();
		    winText.text = "";
		    npc0Text.text = "";
		    npc0Text2.text = "";
		    npc1Text.text = "";
		    npc2Text.text = "";
		    npc3Text.text = "";
		    npc4Text.text = "";
		    npc5Text.text = "";
		    npc6Text.text = "";
		    npc7Text.text = "";
		    npc8Text.text = "";
		    npc9Text.text = "";
		    npc10Text.text = "";
		    npc11Text.text = "";
		    Destroy(guide, 15.0f);
		    GuideTalk.text = "Talk to the ghost and start your journey!";
		    Destroy(GuideTalk, 10.0f);


	}

		void Update (){
        
			if (Input.GetKey ("w")) {
				anim.SetInteger ("AnimationPar", 1);
			}  else {
				anim.SetInteger ("AnimationPar", 0);
			}

			if(controller.isGrounded){
				moveDirection = transform.forward * Input.GetAxis("Vertical") * speed;
			}

			float turn = Input.GetAxis("Horizontal");
			transform.Rotate(0, turn * turnSpeed * Time.deltaTime, 0);
			controller.Move(moveDirection * Time.deltaTime);
			moveDirection.y -= gravity * Time.deltaTime;
		}

	private void OnTriggerEnter(Collider other)
	{
		//触碰物品消失并播放音效
		if (other.gameObject.CompareTag("Pick Up"))
		{
			other.gameObject.SetActive(false);
			_1.Play();
			count = count + 1;
			SetCountText();
		}

		//触碰开关燃放烟花并播放音效
		if (count >= 7)
			butterfly.gameObject.SetActive(true);
		{
			if (other.gameObject == button)
			{
				Fireworks.gameObject.SetActive(true);
				_1.Play();

				npc0Text2.text = " 'My wish is to feel the beauty and warmth of this world, and now my wish has come true, thank you.' ";
				
			}
		}

		//触碰人物显示对话
		//触碰幽灵，幽灵说话并跟随
		if (other.gameObject.CompareTag("NPC0"))
		{
			npc0Text.text = "Hello, I am Bunny you have raised for five years. But last year I fell ill and passed away...For some reason, I came back as a ghost...Can you help me find out the reason?";
			Destroy(npc0Text, 9.0f);
			Ghost.gameObject.SetActive(false);
			Ghost2.gameObject.SetActive(true);

		}

		//触碰npc显示对话1
		if (other.gameObject.CompareTag("NPC1"))
		{
			npc1Text.text = "The ghost of the deceased returned to the world because of the unfulfilled wish of the deceased.";
			Destroy(npc1Text, 7.0f);
		}

		//触碰npc显示对话2
		if (other.gameObject.CompareTag("NPC2"))
		{
			npc2Text.text = "By setting off fireworks, the ghost’s wishes can be told to the gods in the sky to help it come true. Someone on the market knows how to make fireworks. You might as well ask him first.";
			Destroy(npc2Text, 10.0f);
		}

		//触碰npc显示对话3
		if (other.gameObject.CompareTag("NPC3"))
		{
			npc3Text.text = "Seven materials are needed to make fireworks. They are: nitrate, nitrate soil, plant ash, sulfur, charcoal, sucrose, and magnesium.";
			Destroy(npc3Text, 6.0f);
		}

		//触碰npc显示对话4
		if (other.gameObject.CompareTag("NPC4"))
		{
			npc4Text.text = "The market has a complete range of goods, and you can find sucrose here.";
			Destroy(npc4Text, 5.0f);
		}

		//触碰npc显示对话5
		if (other.gameObject.CompareTag("NPC5"))
		{
			npc5Text.text = "There is sea water on the snow mountain, and I have extracted nitrate from that water.";
			Destroy(npc5Text, 6.0f);
		}

		//触碰npc显示对话6
		if (other.gameObject.CompareTag("NPC6"))
		{
			npc6Text.text = "Several scientists once found some magnesium ore at the hyperloop station.";
			Destroy(npc6Text, 6.0f);
		}

		//触碰npc显示对话7
		if (other.gameObject.CompareTag("NPC7"))
		{
			npc7Text.text = "There is a sea of flowers behind the stadium, you can light fireworks there, and butterflies will guide you. The premise is that you have collected seven materials.";
			Destroy(npc7Text, 9.0f);
		}

		//触碰npc显示对话8
		if (other.gameObject.CompareTag("NPC8"))
		{
			npc8Text.text = "Sulfur can be found in the mountains.";
			Destroy(npc8Text, 6.0f);
		}

		//触碰npc显示对话9
		if (other.gameObject.CompareTag("NPC9"))
		{
			npc9Text.text = "The bar caught fire last month and all the plants on the ground were burned. Now some plant ash may remain.";
			Destroy(npc9Text, 7.0f);
		}

		//触碰npc显示对话10
		if (other.gameObject.CompareTag("NPC10"))
		{
			npc10Text.text = "I once found some charcoal in the forest behind the bar.";
			Destroy(npc10Text, 6.0f);
		}

		//触碰npc显示对话11
		if (other.gameObject.CompareTag("NPC11"))
		{
			npc11Text.text = "See the glowing tree? There is some nitrate soil under the tree.";
			Destroy(npc11Text, 6.0f);
		}

	}

	void SetCountText()
	{
		countText.text = "Collection of Items (" + count.ToString() + "/7)";
		if (count >= 7)
		{
			winText.text = "Now you can go to the Sea of Flowers to light the fireworks^_^";
			Destroy(winText, 10.0f);
		}
	}

}

### NaveMeshGoals.cs

    using System.Collections;
    using System.Collections.Generic;
    using UnityEngine;
    using UnityEngine.AI;

public class NavMeshGoal : MonoBehaviour
{

    public Transform goal;
    private NavMeshAgent agent;

    void Start()
    {
        agent = GetComponent<NavMeshAgent>();
        agent.destination = goal.position;
    }


    void Update()
    {
        agent.destination = goal.position;
    }
}

## Contributor to this page:
   * Yifan Li  20007301
