# Lab-02-Microsoft-Azure-AI-Reconhecimento-Facial


# Read text in Vision Studio
In this exercise you’ll use Azure AI service to explore the optical character recognition capabilities of Azure AI Vision. You’ll use Vision Studio to experiment with extracting text from images, without having to write any code.

A common computer vision challenge is to detect and interpret text embedded within an image. This is known as optical character recognition (OCR). In this exercise you’ll use an Azure AI services resource, which includes Azure AI Vision services. You’ll then use Vision Studio to try out OCR with different types of images.

# Create an Azure AI services resource
You can use Azure AI Vision’s OCR capabilities with an Azure AI services multi-service resource. If you haven’t already done so, create an Azure AI services resource in your Azure subscription.

In another browser tab, open the Azure portal at https://portal.azure.com, signing in with the Microsoft account associated with your Azure subscription.

Click the ＋Create a resource button and search for Azure AI services. Select create an Azure AI services plan. You will be taken to a page to create an Azure AI services resource. Configure it with the following settings:
Subscription: Your Azure subscription.
Resource group: Select or create a resource group with a unique name.
Region: East US.
Name: Enter a unique name.
Pricing tier: Standard S0.
By checking this box I acknowledge that I have read and understood all the terms below: Selected.
Select Review + create then Create and wait for deployment to complete.
Connect your Azure AI service resource to Vision Studio
Next, connect the Azure AI services resource you provisioned above to Vision Studio.

In another browser tab, navigate to Vision Studio at https://portal.vision.cognitive.azure.com.

Sign in with your account and making sure you are using the same directory as the one where you have created your Azure AI services resource.

On the Vision Studio home page, select View all resources under the Getting started with Vision heading.

The View all resource link is highlighted under Getting started with Vision in Vision Studio.

On the Select a resource to work with page, hover your mouse cursor over the resource you created above in the list and then check the box to the left of the resource name, then select Select as default resource.

Note : If your resource is not listed, you may need to Refresh the page.

The Select a resource to work with dialog is displayed with the cog-ms-learn-vision-SUFFIX Cognitive Services resource highlighted and checked. The Select as default resource button is highlighted.

Close the settings page by selecting the “x” at the top right of the screen.

# Extract text from images in the Vision Studio
In a web browser, navigate to Vision Studio at https://portal.vision.cognitive.azure.com.

On the Getting started with Vision landing page, select Optical character recognition, and then the Extract text from images tile.

Under the Try It Out subheading, acknowledge the resource usage policy by reading and checking the box.

Select https://aka.ms/mslearn-ocr-images to download ocr-images.zip. Then open the folder.

On the portal, select Browse for a file and navigate to the folder on your computer where you downloaded ocr-images.zip. Select advert.jpg and select Open.

Now review what is returned:
In Detected attributes, any text found in the image is organized into a hierarchical structure of regions, lines, and words.
On the image, the location of text is indicated by a bounding box, as shown here:
An image of the text in the image outlined.

You can now try another image. Select Browse for a file and navigate to the folder where you saved the files from GitHub. Select letter.jpg.

An image of a typed letter.

Review the results of the second image. It should return the text and bounding boxes of the text. If you have time, try note.jpg and receipt.jpg.

Images utilized: ![image](https://github.com/willianosaida/Lab-02-Microsoft-Azure-AI-Reconhecimento-Facial/assets/64991059/2ea851be-7a82-4810-96e5-a06c04990aab)
![image](https://github.com/willianosaida/Lab-02-Microsoft-Azure-AI-Reconhecimento-Facial/assets/64991059/fa343415-474e-47c1-8c69-4cd7e65bc3c3)

