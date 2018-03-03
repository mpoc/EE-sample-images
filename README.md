Extended essay sample images
============================
The sample images used for JPEG encoding library testing in my extended essay "Comparison of lossy JPEG file format image encoders libjpeg-turbo, mozjpeg, jpeg-recompress, jpegoptim and guetzli in terms of encoding speed, compression rate and image quality"

wintertrees.jpg
---------------
![wintertrees.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/wintertrees.jpg)
Source: Image from my personal archive

autumntrees.jpg
---------------
![autumntrees.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/autumntrees.jpg)
Source: Image from my personal archive

sunset.jpg
----------
![sunset.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/sunset.jpg)
Source: Image from my personal archive

poolballs.jpg
-------------
![poolballs.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/poolballs.jpg)
Source: Marco Verch, 2017, *Pool ball set*, viewed January 2018, <[Flickr](https://www.flickr.com/photos/30478819@N08/37188154050/)>. Licensed under [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/)

umbrella.jpg
------------
![umbrella.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/umbrella.jpg)
Source: Bill Harrison, 2014, *Protected*, viewed January 2018, <[Flickr](https://www.flickr.com/photos/bill_harrison/13886342085/)>. Licensed under [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/)

plane.jpg
---------
![plane.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/plane.jpg)
Source: Image from my personal archive

nightshot.jpg
-------------
![nightshot.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/nightshot.jpg)
Source: Image Compression, 2007, *nightshot_iso_100*, viewed January 2018, <[Image compression](http://imagecompression.info/test_images/)>.

ducks.jpg
---------
![ducks.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/ducks.jpg)
Source: Susanne Nilsson, 2013, *Ducks*, viewed January 2018, <[Flickr](https://www.flickr.com/photos/infomastern/11128183215/)>. Licensed under [CC BY-SA 2.0](https://creativecommons.org/licenses/by-sa/2.0/)

culturalcentre.jpg
------------------
![culturalcentre.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/culturalcentre.jpg)
Source: Image from my personal archive

randomimage.jpg
---------------
![randomimage.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/randomimage.jpg)
Source: Generated using the following Java code (code adapted from [How to create a random pixel image in Java](https://www.dyclassroom.com/image-processing-project/how-to-create-a-random-pixel-image-in-java):
```
/**
 * File: RandomImage.java
 * 
 * Description:
 * Create a random color image.
 * 
 * @author Yusuf Shakeel
 * Date: 01-04-2014 tue
 */
import java.io.File;
import java.io.IOException;
import java.awt.image.BufferedImage;
import javax.imageio.ImageIO;

public class Main {
	public static void main(String[] args) throws IOException {
		//image dimension
		int width = 640;
		int height = 320;
		//create buffered image object img
		BufferedImage img = new BufferedImage(width, height, BufferedImage.TYPE_INT_RGB);
		//file object
		File f = null;
		//create random image pixel by pixel
		for(int y = 0; y < height; y++){
			for(int x = 0; x < width; x++){
				int r = (int)(Math.random()*255); //red
				int g = (int)(Math.random()*255); //green
				int b = (int)(Math.random()*255); //blue

				int p = (r<<16) | (g<<8) | b; //pixel

				img.setRGB(x, y, p);
			}
		}
		//write image
		try{
			f = new File("RandomImage.jpg");
			ImageIO.write(img, "jpg", f);
		}catch(IOException e){
			System.out.println("Error: " + e);
		}
	}//main() ends here
}
```

gradient.jpg
------------
![gradient.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/gradient.jpg)
Source: Image from my personal archive, created using image and photo editing software Paint.net

lipsum.jpg
----------
![lipsum.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/lipsum.jpg)
Source: A screenshot of the webpage [Lorem ipsum generator](https://loremipsumgenerator.com/)

dragon.jpg
----------
![dragon.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/dragon.jpg)
Source: Brandon James Scott, 2012, *Dragon Scream*, viewed January 2018, <[Flickr](https://www.flickr.com/photos/brandonjamesscott/7591523382)>. Licensed under [CC BY-NC-ND 2.0](https://creativecommons.org/licenses/by-nc-nd/2.0/)

face.jpg
--------
![face.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/face.jpg)
Source: Jarrett Kupcinski, 2011, *JKPP luligirl*, viewed January 2018, <[Flickr](https://www.flickr.com/photos/kpcnsk/6377666717/)>. Licensed under [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/)

rays.jpg
--------
![rays.jpg](https://raw.githubusercontent.com/mpoc/EE-sample-images/master/rays.jpg)
Sources: ASUNI N, GIACHETTI A, "TESTIMAGES: A Large Data Archive For Display and Algorithm Testing", Journal of Graphics Tools, Volume 17, Issue 4, 2015, pages 113-125, DOI:10.1080/2165347X.2015.1024298
ASUNI N, GIACHETTI A, "TESTIMAGES: a large-scale archive for testing visual devices and basic image processing algorithms", STAG - Smart Tools & Apps for Graphics Conference, 2014.
