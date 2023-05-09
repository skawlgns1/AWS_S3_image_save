# AWS_S3_image_save
AWS_S3 이미지 저장소 
AWS SDK를 사용 하여 S3를 이미지 저장소로 사용

<이미지저장>

#request

POST /images

Content-Disposition: form-data; name="file"; filename="my-image.jpg"

#response

{
  "image": "https://redhood.s3.ap-northeast-2.amazonaws.com/1234my-imag.png"
}




<이미지삭제>

#request

DELETE /images
{
 "image":"https://my-bucket.s3.ap-northeast-2.amazonaws.com/123my-image.jpg"
}
