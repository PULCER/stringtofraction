    func convertStringToFraction(stringNumber: String) -> Float {
        let stringFloat = stringNumber.components(separatedBy: "/")
        let numerator = Float(stringFloat[0]) ?? 0.0
        let denominator = Float(stringFloat[1]) ?? 0.0
        return numerator / denominator
    }
