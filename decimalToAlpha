    /**
     *  十进制转26字母进制
     * @param int $ascii_code
     * @return string
     * @Date: 2019/9/4
     * @Time: 下午1:49
     * @Author: jweiquan
     */
    public function translateAsciiCode($ascii_code)
    {
        if ($ascii_code < 65) {
            return 'Z';
        } elseif ($ascii_code >= 65 && $ascii_code <= 90) {
            return chr($ascii_code);
        } else {
            return $this->translateAsciiCode(ceil(($ascii_code - 90) / 26) + 64) . $this->translateAsciiCode(($ascii_code - 90) % 26 + 64);
        }
    }
