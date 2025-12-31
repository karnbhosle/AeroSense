# API Contract

Request:
{
  city: "Delhi",
  pm25: number,
  pm10: number,
  no: number,
  no2: number,
  nox: number,
  nh3: number,
  co: number,
  so2: number,
  o3: number
}

Response:
{
  predictedAQI: number,
  category: string
}
